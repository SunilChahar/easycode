# easycode
Spring Boot, MongoDB, Angular Restful API Tutorial
Build a Fully-Fledged Todo App with Spring Boot & mLab(i.e. online database) in the Backend and Angular4.X in the frontend.

Requirements
Java - 1.8.x

Maven - 3.x.x

mLab - online database

Steps to Setup
1. Donwlad the zip file
UI.zip
backend-spring-boot.zip

2.For mLab for online mongoDB:
create database using free plan.
create user(i.e. username/password).
MONGODB (MongoProperties) - spring.data.mongodb.uri=mongodb://XXXXXXX:XXXXXXX@ds239368.mlab.com:39368/tododemo

3. For Build and run the backend app using maven: backend-spring-boot
Unzip the folder and use below steps
cd backend-spring-boot
mvn clen install
mvn spring-boot:run


4. Run the frontend app using npm
cd angular-frontend
npm install
npm serve --open
Frontend server will run on http://localhost:4200


ENJOY THE PROJECT LOOKS AND SHARE FEEDBACK
