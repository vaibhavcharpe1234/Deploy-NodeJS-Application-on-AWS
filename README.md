Deploying NodeJS Application on AWS 🎉

1. Launch EC2 instance of ubuntu image on AWS
2. Take ssh of EC2 instance on Mobaxterm
3. Clone the source code repository on the EC2 instance

git clone https://github.com/verma-kunal/AWS-Session.git

4.	Setup the following environment variables - (.env) file

DOMAIN= ""
PORT=3000
STATIC_DIR="./client"

PUBLISHABLE_KEY=""
SECRET_KEY=""

5.	Open the port 3000 in security group of instance
6.	Initialise and start the project

npm install
npm run start

7.	  Verify application on browser by public_ip:3000

Application is deployed on AWS 🎉
