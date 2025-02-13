
⭐ Introduction
This project is a Full Stack Todo List Application which is built using the MongoDB, NodeJS, ExpressJS, CSS, Javascript. It implements all the basic functionalities of a todo list, i.e, CRUD Operations (Create Read Update Delete).

Users are able to Create new tasks.
Users are able to Read the created tasks data.
Users are able to Complete the task by checking off the task with a strike through.
Users are able to Delete the task.
Users are able to Update the tasks with many customized options. Users are able to View a Banner with current date-time.
Users can Check the count of remaining tasks, Complete all tasks together, Delete all completed tasks together.
Users can View All, Incomplete, Completed Tasks.
Users can mark Due Date & Priority Levels for the Tasks.

🔥 Getting Started With The Project
Fork the Project in your Repository.
Clone the Forked Repository in your Local System.
Install & Configure - NodeJS, MongoDB, Robo3T.
Create '.env' file & Set the Environment Variables in it, as per the 'ENV_FORMAT.json' file.
Run 'npm install' in GitBash Terminal
Go to 'package.json' & inside the 'SCRIPTS', find "start":"...."
Change it to - "start": "nodemon index.js",
If you want to run the project in development mode locally then go to '.env' file & set,
ENVIRONMENT=development
DEPLOYMENT=local
If you want to run the project in production mode locally then go to '.env' file & set,
ENVIRONMENT=production
DEPLOYMENT=local
Change "module.exports = production" to "module.exports = development" or vice-versa in the 'environment.js' file as per the requirement.
Run 'npm start' in GitBash Terminal
Enjoy :)
