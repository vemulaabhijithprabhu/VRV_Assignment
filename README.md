# VRV_Assignment
This is a Role Based Access Control application using Nodejs, Express, Passport Js, etc. You can use this application as the starting point for whatever project you are going to build which needs authentication and authorization.
o start setting up the project
Step 1: Clone the repo

git clone https://github.com/trulymittal/role-based-access-control
Step 2: cd into the cloned repo and run:

npm install
Step 3: Put your credentials in the .env file.

PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
Step 4: Install MongoDB (Linux Ubuntu)

See https://docs.mongodb.com/manual/installation/ for more infos

Step 5: Run Mongo daemon

sudo service mongod start
Step 6: Start the app by

npm start
