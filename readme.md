#### Package the project to generate jar files 
mvn package

#### To build the image in Maven, you can use a simpler Docker command line:

docker build -t springio/gs-spring-boot-docker .

#### Macoratti's solution

http://www.macoratti.net/19/02/dock_imgfile1.htm

-p <your port>:<port exposed in container>