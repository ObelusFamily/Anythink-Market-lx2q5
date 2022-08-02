## Setting up local environment

Step 1: install docker. You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.

Step 2: Then, run docker-compose up from the project root directory to load Anythink's backend and frontend.
If Docker is working correctly, the backend should be running and able to connect to your local database.

Step 3: Let's test this by pointing your browser to http://localhost:3000/api/ping