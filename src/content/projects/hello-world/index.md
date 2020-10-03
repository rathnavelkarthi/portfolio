---
title: "Xploitspy"
tags: ["Project", "", "Android SPY","", "XploitSPY","", "NODE JS","", "GraphQL"]
date: "2020-05-13"
---
XploitSPY is an Android Monitoring / Spying Tool.
A cloud based Android Spying or Monitoring Tool, powered by NodeJS.

<H4>HOW TO INSTALL XploitSPY IN AWS UBUNTU </H4><br>
<h4>NOTE:: WHILE CREATING EC2 INSTANCE IN AWS USING UBUNTU. <br>
OPEN THE PORTS TO HTTPS,HTTP AND SSH</h4>
<h5>1.java is essential for comipling the apk so install java</h5>
sudo apt install openjdk-11-jre-headless
<h5> 2.install NodeJS </h5>
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs <br>
# Using Debian, as root<br>
curl -sL https://deb.nodesource.com/setup_14.x | bash -
apt-get install -y nodejs
<h5>3.install PM2</h5>
sudo npm install pm2 -g
<h5>4.Clone this repository</h5>
git clone https://github.com/XploitWizer/XploitSPY.git
<h5>5.change to server dir</h5>
cd server
<h5>6.Run these commands</h5>
npm install <- install dependencies<<br>
sudo pm2 start index.js <-- start the script <br>
sudo pm2 startup <- to run XploitSPY on startup <br>
Default Username: admin & Default Password: password <br>
 <h5>use the public ip which is provided by aws instance</h5>

<h3><a href="http://18.224.37.145/">XploitSPY</a></h3>
 <p>check out the service</p>
