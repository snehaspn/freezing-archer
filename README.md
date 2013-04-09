# Something
Project based on [Vagrant AWS Provider](https://github.com/mitchellh/vagrant-aws) project 

## Prerequisits
EC2 account
EC2 keys + SSH private key 
Vagrant 1.1+
Vagrant AWS Provider -> available [here](https://github.com/mitchellh/vagrant-aws)

## Installation notes
Follow instructions on Vagrant AWS plugin page
Inside of the Vagrant folder create a copy of the cfg_template and name it your_username.cfg
Fill it in with you config data
And then run vagrant up --provider=aws

