# friendfinder
Friend finder is a simple dating app utilizing Node.js and Express. It is based off of questions pulled from Buzzfeed, and matches users based on their responses to 10 questions. The closest set of user responses is displayed as a match.

The app can be found at the following Heroku deployment
https://evening-temple-10084.herokuapp.com/survey

To install and run the application on a local machine, follow these instructions.

After cloning the repository, run npm install in the git directory to install the required dependencies. 

Next, set the `PORT` environment variable to the value of your choice. An example is shown below.

 PORT=3000;
	
After the `PORT` environment variable has been set, run the Node.js application with the command below.

	node server.js

Now simply point your browser to localhost:3000 (or whatever port you selected) and enjoy the survey. 