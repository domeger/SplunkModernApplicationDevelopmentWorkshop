# Modern AppDev Workshop

This repo contains materials for a hands-on workshop demonstrating how to use Splunk in a modern application development environment using technologies like Docker, Node.js, Javascript, Bitbucket, Jenkins, and New Relic.   

During the workshop you will take a running application, clone it to your local machine, make changes to the source code, push and commit those changes to the repo in Bitbucket and have Jenkins rebuild and re-deploy your application in docker.  

Start with the <a href="./Modern AppDev Workshop Student Guide -docker.docx">Student Guide</a> and it will walk you though step by step instructions for installing the pre-requisites and working through the workshop.  If you'd like to view the Slides that accompany the workshop, just check them out here as well.  



## Pre-requisites

### Hardware
The workshop will spin up a number of docker containers in a cluster and each will require a significant amount of memory on your local machine.   This environment will run on a machine with 8GB of RAM, but it is recommended to run with at least 16GB of RAM. 

### Git
In this workshop you will use Git to clone a repository from Bitbucket and make changes.   To do this you will need to have Git installed on your local machine.  

### Docker
The entire workshop runs in Docker containers so you'll need to have docker & docker-compose installed on your laptop.   The workshop will spin up a number of containers in a cluster.  There will be one container for the application, one for Jenkins, one for Bitbucket and one for Splunk Enterprise.   
