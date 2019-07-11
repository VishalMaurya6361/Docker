Knowlege Used: Dockerfile, port mapping, -r tag, python


Description:

  This is an simple application using python , flask, and redis.
  I have used python 2.7 as a base image and install flash and redis upon it using -r tag in RUN command in DockerFile.
  After running the container it will open port 80 on the docker container.
  We can map this port by using below mapping command and run in deattach mode using -d tag

      docker run -d -p 8080:80 vishalmaurya/sayhello

By default, this image will render a Html page, having message "Hello Word!" in which "World" is coming from environment variable NAME.
