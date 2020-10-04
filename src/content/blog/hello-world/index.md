---
title: "How to use exploit spy on aws"
tags: ["Hello", "World", "First", "Post"]
description: "1"
author: "Rathnavel"
date: "4-10-2020"
---

First Create a ec2 instance in aws. (only for educational purpose)

Choose any linux distro ( I have used ubuntu ).


while creating a instance,Create it with the acess to ssh,http and https protpcols.

Then follow these acess.

Connect to your server via SSH  

Install JRE 9+

Debian, Ubuntu, Etc

sudo apt install openjdk-11-jre-headless

Fedora, Oracle, Red Hat, etc

sudo yum install java-11-openjdk-devel"

To use pm2 you should install nodejs first.

install PM2

sudo npm install pm2 -g

Clone this repository

git clone https://github.com/XploitWizer/XploitSPY.git

Now change to the server directory in the xploitspy dir and run these commands

npm install <- install dependencies

sudo pm2 start index.js <-- start the script

sudo pm2 startup <- to run XploitSPY on startup

Default Username: admin & Default Password: password

In your browser navigate to http://<public ip thats been given to you by the aws>
  
This is my xploitspy server. (dont try the Same login id cause i have chaged lol)

http://18.224.37.145/ 

DO CHECK MY PROJECT TO

https://www.rathnavelkarthi.in/projects/hello-world/
