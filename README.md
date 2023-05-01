# Lab: AWS: Cloud Servers

## Overview

Deploy a Node.js server to AWS EC2

## Resources

## Feature Tasks

Deploy a simple Node.js server to EC2, using Elastic Beanstalk

- Choose a server you've built previously
  - Option 1: A simple API or Web Server
  - Option 2: A socket.io event Hub
  - The server **should not** require a database
  - Check in your server to GitHub

**Task 1:**

- Create a new environment, using Elastic Beanstalk from the AWS Control Panel (GUI)
- Manually deploy your application to this environment by uploading a .zip file

**Task 2:**

- Using the same server, create a new environment using Elastic Beanstalk from your terminal
- Manually deploy your application to this environment by using `eb deploy`

## Documentation

- In your `README.md` include:
  - The links to both of your deployed servers (GUI deploy and CLI deploy)
  - Document your processes

## Elastic Beanstalk Link (GUI)

ec2-54-212-42-68.us-west-2.compute.amazonaws.com

## CLI Link

https://us-west-2.console.aws.amazon.com/ec2/home?region=us-west-2#Home:
## Processes:

#### On your terminal:
- aws configure
- eb init
- eb create
