
# Progressive Web App with express server, nodejs application with docker Conatiner

```ProgressiveWebApp

Progressive Web App using js, HTML, bootstrap, css.

Implementation of Progressive Web App


# Installation


```javascript

    // then install the npm modules using
     
    npm install


```

# docker-compose

```
>>>>To install docker compose for the steps
$ sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
$ sudo chmod +x /usr/local/bin/docker-compose

OR
 
$ apt-get install docker-compose


>>>>to check the versions of the docker and docker-compose
    $ docker --version
    $ docker-compose --version


>>>>first start the docker service by using command
    $ service docker start

```

# Building docker image

```bash

    docker build -t <imagename:version> .
    example :-  docker build -t testing_pwa_node:latest

```

# Running docker container


```bash

    // 9005 port is given since the docker file contains 9005 port
    docker run -it -d -p <outside-port-of-your-choice>:9005 <imagename:version>

    example: - docker run -it -d -p 5000:9005 testing_pwa_node:latest

```

# Open Chrome browser and run

```browser

    localhost:5000

```

# docker important commands

```
    $ docker --version
    $ docker images
To check running docker images
    $ docker ps
To stop a running process
    $ docker stop <docker-image-name>
To build a docker image
    $ docker build -t <image-name>
NOTE - Must contain Dockerfile

```

# Topic Covered :-

```Topics

1. Introduction to Progressive Web App
2. Accelerated Mobile Pages
3. AMP vs PWA vs Native Apps
4. PWA Advantages
5. What exactly the service worker is?
6. Working of service worker
7. Web Manifest file
8. Creation of mainifest file
9. Working with the JSON
10. DOM and service worker thread
11. Life cycle of service worker
12. Javascript Promise
13. navigator object
14. Chrome dev tools
15. Audit with lighthouse tool
16. Web app to device home screen

