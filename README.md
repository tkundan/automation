# automation

We are Dockerizing a Java application using jenkins. Jenkins is installed on Centos 7 and running on port number 9090.
1) Here we have taken a small java project
2) We are creating WAR file using maven
3) Once the war file has been created, we use it to create docker image 
4) Finally we deployed that image which can we verified using following link 
5) http://107.21.71.176:8080/JenkinsWar/

Jenkins Link -> http://107.21.71.176:9090/job/prudential/
username - kundan
password - Shared with HR

You can find Jenkinsfile in the repository which guide the comple Continuous integration and Deployment.
I have created a webhook in github which means as soon as user push the code the build will start. 


this repository contain Java application, Dockerfile ,Jenkinsfile and README.md file .

Please contact me if you have any questions.
This branch is for Story JRO-170
