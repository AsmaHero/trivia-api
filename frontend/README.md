# Full Stack Trivia API  Frontend

## Getting Setup

> _tip_: this frontend is designed to work with [Flask-based Backend](../backend). It is recommended you stand up the backend first, test using Postman or curl, update the endpoints in the frontend, and then the frontend should integrate smoothly.

### Installing Dependencies

#### Installing Node and NPM

This project depends on Nodejs and Node Package Manager (NPM). Before continuing, you must download and install Node (the download includes NPM) from [https://nodejs.com/en/download](https://nodejs.org/en/download/).

#### Installing project dependencies

This project uses NPM to manage software dependencies. NPM Relies on the package.json file located in the `frontend` directory of this repository. After cloning, open your terminal and run:

```bash
npm install 
npm start
```

>_tip_: **npm i** is shorthand for **npm install**. node js is needed to run the application

## Required Tasks

## Running Your Frontend in Dev Mode

The frontend app was built using create-react-app. In order to run the app in development mode use ```npm start```. You can change the script in the ```package.json``` file. 

Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page will reload if you make edits.<br>

```bash
npm start
```
## Request Formatting
You need to update requests according to your db ports and make sure that the server of db is allow acess origins for all servers especially the localhost:5000 for DB. The front end is working on localhost:3000. 

The frontend should be fairly straightforward and disgestible. You'll primarily work within the ```components``` folder in order to edit the endpoints utilized by the components. While working on your backend request handling and response formatting, you can reference the frontend to view how it parses the responses. 

After you complete your endpoints, ensure you return to and update the frontend to make request and handle responses appropriately: 
- Correct endpoints
- Update response body handling 
At the end, the project will work , enjoy.