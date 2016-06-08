## Jenkins Jekyll Dockerfile
A docker image which has all the prerequisites for building a Jekyll site using alpine linux.

### Base Docker Image

* [jenkins:alpine](https://github.com/michaelneale/jenkins-ci.org-docker)

### Usage
    docker run -p 8080:8080 -p 50000:50000 bhavikk/jenkins-jekyll