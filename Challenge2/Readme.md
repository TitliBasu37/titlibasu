How to install

Create an EC2 Linux instance on AWS
SSH into the instance
Install Python 3 and git on your instance
sudo yum install python3 git
Install pipenv
sudo pip3 install pipenv

Install project dependancies
pipenv install

How to run
python3 get_metadata.py