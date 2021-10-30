#### Package the project to generate jar files 
mvn package

#### To build the image in Maven, you can use a simpler Docker command line:

docker build -t springio/gs-spring-boot-docker .

#### Macoratti's solution

http://www.macoratti.net/19/02/dock_imgfile1.htm

-p <your port>:<port exposed in container>

#### To list your container repo on aws

aws ecr describe-repositories --repository-name <your repo>

#### How to Create an Stack

aws cloudformation create-stack --stack-name <stack name> --template-body file://$PWD/<path on project>

$PWD is the currenty directory

--capabilities CAPABILITY_IAM to create IAM Stacks

