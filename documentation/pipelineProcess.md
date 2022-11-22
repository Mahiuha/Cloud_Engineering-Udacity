# pipeline process using circleci

- when we make changes in the repository and push the code to github magic happens.
- circleci update the frontend and the backend immediately deploying them and adding/updating environment variables to elastic beanstalk.
- and this magic have some steps....
- first, it installs packages for the frontend and the backend
- then build the frontend and the backend
- then it deploys them to aws.