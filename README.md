# Docker-ML-App

Run the DockerFile by running the command - `docker build -t api_name .` 
(give whatever api_name you want)

It will take some time to build the docker image.

Then you can run docker by using the command - `docker run -p 8000:8000 api_name`
8000 is the port number mapping from local host to docker image

Then you can view the web app at 0.0.0.0:8000 (for linux and mac users when virtualization is enabled).
But if your system is not compatible and you had to install docker toolbox, then open a docer terminal and see the
 IP address at which docker is running and paste that into browser.
