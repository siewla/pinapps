# Pin Apps

## Application Description
This app serves to help its users organise and share the apps they commonly use.

## Team Members/Collaborators
#### 1. [Chee Kiong Neo](https://github.com/neocheekiong/)
#### 2. [Siew La Pang](https://github.com/siewla/)

## Application link
#### 1. [PinApps Front-End](https://pinapps.herokuapp.com/)
#### 2. [PinApps Back-End](http://pinapps-backend.herokuapp.com/api/apps/all)

## Github Repositories
#### 1. [Back-End Repo](https://github.com/siewla/pinapps-backend)
#### 2. [Front-End Repo](https://github.com/siewla/pinapps-frontend)

## Database/Storage
* **MongoDB** is a document-oriented NoSQL database used for high volume data storage
* **Cloudinary** is a cloud service that offers a solution to a web application's entire image management pipeline.

## Technologies
### Backend
* **capture-website** is used capture screenshots of websites
* **bcrypt** is used to hash and store passwords in database
* **cors** provides a Connect/Express middleware that can be used to enable CORS with various options.
* **express-jwt**  provides Express middleware for validating JWTs (JSON Web Tokens) through the jsonwebtoken module
* **google-auth-library** is Google's officially supported node.js client library for using OAuth 2.0 authorization and authentication with Google APIs.
* **jsonwebtoken** is a compact, URL-safe means of representing claims to be transferred between two parties. 
* **mongoose** provides a straight-forward, schema-based solution to model the application data. It includes built-in type casting, validation, query building, business logic hooks and more, out of the box.
* **morgan** is a HTTP request logger middleware for node.js
* **node-fetch** is a light-weight module that brings window.fetch to Node.js
* **nodemailer** is to send e-mails from Node.js

### Frontend
* **axios** is a promise based HTTP client for the browser and node.js
* **mdbreact** is an UI KIT for building responsive, mobile-first websites and apps - free for personal & commercial use.
* **react-google-login** is a Google oAUth Sign-in / Log-in Component for React
* **serve** is to serve a static site, single page application or just a static file.
* **react-loading** is used to load animations for React projects. 
* **react-promise-tracker** is a simple promise tracker React Hoc. 
* **react-moment** is react component for the moment date library.

## Objective/Minimum Viable Product (MVP)
A working full-stack application using  **MERN** (MongoDB, Express, React and Node.js) and **CRUD** (Create, Read, Update and Delete) that adheres to **MVC** (Models, Views, and Controllers) file structure.

## Project Scope
* User is able to view top 3 apps in each category.
* User is authenciated via Google oAuth or JWT.
* User is able to view all comments after authenciated
* User is able to add/edit/delete comments after authenciated
* User is able to add new app after authenciated
* User is able to reset password
* User is able to like the app to add to my apps page

## Approaches Taken
* set up a basic MVC structure with basic CRUD route in the backend
* set up database with collections and schema validation in the MongoDB
* built authentication page in the frontend
* host the backend and frontend to heroku

## Accomplishments
* The application is meeting the mininum viable product (MVP)'s requirements.
* The Authenciation layer implemented using JWT, real email has to be used as account needed to be activated via token. 

## Difficulties faced
* The authentication layer - nodemailer is easier to implement than @sendgrid/mail (the mail will go to spam)
* The env parameter for react app must started with 'REACT_APP_'

## Wireframe Design and User Stories
### Landing Page (Not Signed In)
### About (Not Signed In)
### Get Started (Not Signed In)
### Login (Not Signed In)
### Landing Page (Signed In) 
### My Apps (Signed In)
### Show Apps By Category

## RESTful Routes
<table><tr><td>
 <img src="/routes.png" />
</td></tr></table>

## Additional Features were under Considerations
* App submission and approval workflow - app can only be added to database upon admin approved it.
* App rating by stars
* Apps filtered by #hashtag

## Credits
* All the **alpha trials users** and **fellow coursemates** 
