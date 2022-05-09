# Project Pipleline

## Github

Developers commit and push code to the code repository on github, which triggers CircleCi to rebuild the web app.

## CirlceCi

Circleci reaches into the config.yml in the .CircleCi folder and starts executing the jobs that exists in the file which installs backend and front end dependencies then starts building the frontend and backend then CircleCi starts deploying the Application to AWS and setting production environment variables which were stored in CircleCi Application’s configuration thus automating installing dependencies, building and deploying the web app.
