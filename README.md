# What is this project?
Its a information page website where one can share informations and datasanonymously and read others informations by signup/login. 
User can update his profile also.


**I built this project to practice using Node.js, Express.js, EJS, a lot of NPM tools & MongoDB/Mongoose through a functional real-world application:** 

## How to run this project on your local machine

1. Ensure that you have NPM and Node.js installed on your machine
2. Make sure that you have MongoDB installed and properly configured on your machine. These instructions do not cover how to run the project with a DB that is being run on an external server, minimal changes to the code are required for this to work. 
3. In your project directory run `npm install` to install all the required dependencies.
4. Once dependencies are installed head to the **app.js** file and locate the `mongoose.connect()` function. By default the name of the database is `UserDB` but you may change it to whatever you like at the end of the string.
5. Start up MongoDB with the `mongod` command followed by any flags if your local configuration requires it.
6. Start the application with `node app.js` and head to `localhost:3000` in your browser of choice.
