## DAT250: Software Technology Experiment Assignment 1 Report

### Objective of the assignment:
The objective of this assignment is to set up and validate a comprehensive Software Development Environment (SDE). 
This environment will facilitate effective software development tasks throughout the course.

### Tasks done:
In this lab exercise I have installed java development environment (JDK), 
IntelliJ IDE, the Gradle software build tool, a git client and Podman to execute containers.

After all the installations, I created accounts on GitHub and DockerHub to store and manage projects and containers.

Next, I had to make an already existing application production ready: 
- I moved the source code of the application into a version-controlled environment using Git and GitHub.
- I set up Gradle as the build system for the application.
- Then I refactored the code and made a new function called convertUnit(). 
- I made new tests for the app.java code in AppTest.java. 
- I packaged the application as a container for easier deployment and distribution.

For the containerization of the Application I created a Dockerfile that describes how the application will be containerized.
I built a container image using Podman and verified its existence.
At last I pushed the container image to DockerHub, making it publicly accessible for deployment.

### Technical problems:
I didnt experience any technical problems during this assignment. 
Everything is working fine and I have no pending issues. 

### Results:
By the end of the assignment, a comprehensive software development environment was successfully set up and validated. 
A Java web application was also retrieved, improved, containerized, and made available on DockerHub, ensuring it is "production-ready".


URL to my container in dockerhub: https://hub.docker.com/repository/docker/jvalen01/dat250/general

