# snapshotalyzer-30000

Demo project to manage EC2 snapshots

## About

This project is a demo and uses boto3 to manage instance snapshots.

## Configuring

shotty uses the config file created by the AWS CLI. EX:

`aws configure --profile shotty`

## Running

`pipenv run ipython shotty/shotty.py <command> <subcommand> <--project=PROJECT>`

*command* is list, start or stop
*subcommand* - depends on command
*project* is optional
