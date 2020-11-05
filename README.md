# Steps to follow to build the Hello World with Docker

## Step 1
### go to the repository with the files and type this command in terminal:
 `docker build -t my-first-go-app .`

### then you can type this command to run your application
 `docker run -d -p 80:80 my-first-go-app`

### this will make your go app run in docker in localhost
### you can go to your browser and type *localhost:80* and your app will run

### to see the docker container on you can type
 `docker ps`

### to stop your container you can type the command dcoker stop with the ID of your container
 `docker stop 123456abcdef`