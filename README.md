# docker-challenge-template
Docker Challenges: Deployment and Scaling of Web Applications
This repository contains the documentation and necessary files to deploy and scale a multi-container web application using Docker, as outlined in Challenges 3 and 4.
Setup
Extract the contents of challenge3.zip into the root directory and create a .env file with the necessary configuration variables.

Running the Application
docker-compose up -d
Expected Outcomes
Accessing http://localhost:8080/api/books returns a JSON list of books.
Accessing http://localhost:8080/api/books/1 returns details of the first book.
Challenge 4
Scaling the Service
To scale the node-service from one to three instances:
docker-compose up -d --scale node-service=3
Observations
After scaling, accessing http://localhost:8080/api/stats should yield responses from different instances.

Contributing
To contribute to this project, please fork the repository and submit a pull request with your proposed changes.
