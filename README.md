# AWS SQS NodeJS Example

Follow the instructions below on an EC2 Ubuntu instance. This tutorial will help you setup the AWS SDK using NodeJS. If you have any questions please contact me!

```
sudo su
apt-get update
apt-get upgrade -y
curl --silent --location https://rpm.nodesource.com/setup_8.x | sudo bash -
sudo yum -y install nodejs
git clone https://github.com/ehayanis/aws-sdk.git
cd aws-sdk
npm install
cp config-sample.json config.json
```

***NOTE: Here you will want to edit config.json with your AWS keys.***

```
node app.js
```
