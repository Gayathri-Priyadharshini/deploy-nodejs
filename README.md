# Deploying a Node Js Application on AWS EC2

### Testing the project locally

1. Clone this project
```
git clone https://github.com/Gayathri-Priyadharshini/deploy-nodejs
```
2. Setup the following environment variables - `(.env)` file from srtipe dashboard
```
DOMAIN= ""
PORT=3000
STATIC_DIR="./client"

PUBLISHABLE_KEY=""
SECRET_KEY=""
```
3. Initialise and start the project
```

apt install nodejs
node -v
apt install npm

npm install
npm run start
```

### Set up an AWS EC2 instance

1. Create an IAM user & login to your AWS Console
2. Create an EC2 instance
3. Connecting to the instance using ssh

### Configuring Ubuntu on remote VM

1. Updating the outdated packages and dependencies
```
sudo apt update
```

### Deploying the project on AWS

1. Clone this project in the remote VM
```
git clone https://github.com/verma-kunal/AWS-Session.git
```
2. Setup the following environment variables - `(.env)` file
```
DOMAIN= ""
PORT=3000
STATIC_DIR="./client"

PUBLISHABLE_KEY=""
SECRET_KEY=""
```

3. Initialise and start the project
```

apt install nodejs
node -v
apt install npm

npm install
npm run start

```

> NOTE - We will have to edit the **inbound rules** in the security group of our EC2, in order to allow traffic from our particular port

### Project is deployed on AWS 🎉

<img width="956" height="536" alt="image" src="https://github.com/user-attachments/assets/aeaa1c50-8d14-4bc5-aed1-5bd906ed6acc" />

