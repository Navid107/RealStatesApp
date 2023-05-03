# Node.JS REST API with React and Refine 


## A fully functional project written in Node.js showing how to craete a REST API

This is a simple CRUD appolication where every part of this project is sample code which shows how to do the following:

* Create a custom web server with Node.JS using HTTPRouter
* Create a simple REST API that serves Client and easy to manage
* Create a simple charts or graphs with Refine
* Create a Mongoose DataBase which saves the data in cloud 
* Create a front end with React 

<br/>

## Demo 

* <a href="https://realdealagency.netlify.app/">Live Demo</a>
* Login 

<img width="300" alt="Screenshot" src="https://user-images.githubusercontent.com/90425833/235983495-0b6e37da-b0e2-4726-8237-53c710418ad0.png">
<img width="300" alt="Screenshot" src="https://user-images.githubusercontent.com/90425833/235983987-4b6f7d0e-34ec-4986-8e3a-bc183178e0eb.png">

* View the properties 
<img width="300" alt="Screenshot" src="https://user-images.githubusercontent.com/90425833/235984064-3613d864-2180-4117-9a78-5f5daf90aa0b.png">

* Create a property
<img width="300" alt="Screenshot" src="https://user-images.githubusercontent.com/90425833/235984347-6dcc6727-fe9f-4a32-bb59-181e14804d62.png">

* Property details 
<img width="300" alt="Screenshot" src="https://user-images.githubusercontent.com/90425833/235984716-7af9dfcc-f79e-4b43-88c8-e6969e382560.png">


* Profile page
<img width="300" alt="Screenshot" src="https://user-images.githubusercontent.com/90425833/235984513-26fc6c97-4908-462c-a9d3-29060fc5a702.png">





## How to install dependecy for this app 

Please follow the steps to intall all dependencies to use this repo 

1. Clone this project. 
2. Set up a local mangoose database or use <a herf="https://www.mongodb.com/atlas/database"> MongoDB Cloud</a>.
3. In server folder create a .env file and inside .env file create a variable "MONGODB_URL" and pass your mongoDB to it.
4. Create an account in <a herf="https://cloudinary.com/">Cloudinary</a> and inside .env file pass these variables and 
    CLOUDINARY_CLOUD_NAME = "", CLOUDINARY_API_KEY = "", CLOUDINARY_API_SECRET = "".
5. in Client folder create a .env file and indide .env file create a variable REACT_APP_GOOGLE_CLIENT_ID = "", in <a                herf="https://console.cloud.google.com/"> Google Cloud</a> create an project and pass the value of Client ID into .env file.
6. npm intall

## Available Scripts

### Running the development server.

```bash
    npm run dev
```

### Building for production.

```bash
    npm run build
```

### Running the production server.

```bash
    npm run start
```

