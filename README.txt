


After repo is cloned/downloaded, open your commandline and navigate to project directory.

Install NPM packages:
npm install

Start the API server:
node index.js


Now that the API is started, open a new commandline to make requests.

To submit a GET request: 
curl http://localhost:3000/

To submit a POST request using a simple JSON object containing a name and email: 
curl -X POST -H "Content-Type: application/json" -d '{"name":"SpongeBob Squarepants","email":"ilovegary@yahoo.com"}' http://localhost:3000/api/users
