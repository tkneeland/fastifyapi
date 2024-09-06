

Open terminal & go to project directory, type to start API: node index.js

Now that the API is started, open a new terminal to make requests.





To submit a GET request, type: 

curl http://localhost:3000/


To submit a POST request using a simple JSON object, type: 

curl -X POST -H "Content-Type: application/json" -d '{"name":"SpongeBob Squarepants","email":"ilovegary@yahoo.com"}' http://localhost:3000/api/users
