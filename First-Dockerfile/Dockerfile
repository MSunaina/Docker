FROM ubuntu:latest

#set working directory in the image

WORKDIR /Application

#Copy the files from host file system to image file system

COPY . /Application 

#Install necessary packages

RUN apt-get update && apt-get install -y python3 python3-pip

#Set Environment variable

ENV NAME world

#Run the commands to start the app

CMD ["python3","app.py"]
 



