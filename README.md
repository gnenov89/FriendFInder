# FriendFInder https://friendfinder-123.herokuapp.com/
Pet Friend Finder is an app that helps find your most compatible pet type. This is primarily an exercise in setting up an Express server and handling routing. On the front end the user fills out a survey form, and on the back end an Express server handles the routing to help determine the right type of pet.

The survey has 10 questions. Each answer is on a scale from 1 to 5 based on the user's level of agreement or disagreement with the question. The server.js file requires express and body-parser as npm packages, as well as node's internal path package. html_routes.js contains a GET route for displaying the survey, as well as a default USE route for the home page. api_routes.js contains a GET route to display all possible matches as well as a POST route to handle incoming survey results and perform the compatibility logic.

Also used in this mini project are jQuery, Bootstrap, and a custom Bootstrap theme.

