...
# first DEPI project

## simple ansible project "install nodejs app"

### to prepare the app for startup, installing all the dependencies
`npm install`
### to start the application
`npm start or node app/server.js`

### to build the image from Dockerfile
`docker build -t nodejs-app:1.0 .`

### to start the built docker image
`docker run nodejs-app:1.0`

### to build an archive file
`npm pack`
