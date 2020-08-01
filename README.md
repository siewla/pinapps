# Pin Apps

## Application Description
This app serves to help its users organise and share the apps they commonly use.

## Team Members
#### 1. [Chee Kiong Neo](https://github.com/neocheekiong/)
#### 2. [Siew La Pang](https://github.com/siewla/)

## Application link
#### 1. [Back-End Repo](https://github.com/siewla/pinapps-backend)
#### 2. [Front-End Repo](https://github.com/siewla/pinapps-frontend)

## Database/Storage
* **MongoDB** is a document-oriented NoSQL database used for high volume data storage

## Technologies
* **Method-override** is used to to convert HTTP verbs such as PUT or DELETE in places where the client doesn't support it
* **Bcrypt** is used to hash and store passwords in database
* **Express-session** is used to store the user state with each given being assiged a unique session. 

## Objective
The objective of the project is to build a working full-stack application using  **MERN** (MongoDB, Express, React and Node.js) and **CRUD** (Create, Read, Update and Delete) that adheres to **MVC** (Models, Views, and Controllers) file structure.

## Approaches Taken
* set up a basic MVC structure with basic CRUD routes.
* set up database with collections and schema validation in the MongoDB
* built authentication page
* linked the app to heroku

## Accomplishments
* The application is meeting the mininum viable product (MVP)'s requirements.

## Difficulties faced
* The authentication layer - nodemailer is easier to implement than @sendgrid/mail (the mail will go to spam)
* Sign in with google won't redirect even though the jwt token is saved in the cookie. 
* The env parameter for react app must started with 'REACT_APP_'

## Wireframe Design and User Stories


## RESTful Routes


## Additional Features were under Considerations

## Credits
* All the **alpha trials users** and **fellow coursemates** 
