# User's_Self_Memorandum_App_using_nodejs_and_React_js

Keeping notes is generally a to maintain in the forefront of one's awareness.

# Installation

# Prerequisites

# 1. Install Python
Install python-3.7.2 and python-pip. Follow the steps from the below reference document based on your System Requirements. Reference: https://docs.python-guide.org/starting/installation/
# 2. Install Mongo db
Install mysql-8.0.15. Follow the steps form the below reference document based on your System Requirements. Reference: https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-windows/

# 3. Install requirements
cd frontend
1. npx create-react-app my-app
2. npm install
cd backend
node install

# 4. Create Database in Mongodb
create database in mongodb by using the database name Note Zipper;

# 5. Edit project settings
#open .env file

#Edit Database configurations with your mongodb configurations.
#Search for DATABASES section.

MONGO_URI=mongodb://127.0.0.1:27017/notezipperDB
JWT_SECRET=somesecret
NODE_ENV=newuser
PORT=3000

# 6. save the file
     cltr+s
     
# 7. Run the server
#Make migrations
1.cd backend 
node server.js
2.cd frontend
npm start

# 8. URLs
Login 
![image](https://user-images.githubusercontent.com/82249340/213255691-c6fdab27-933a-4f2f-a879-37ac8cd12681.png)

