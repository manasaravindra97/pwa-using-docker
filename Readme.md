# Sample nodejs application with docker Conatiner


# Installation


```javascript

    // clone the application with git clone

    // then install the npm modules using
     
    npm install


```


# Running the application


```javascript


    node server.js


```


# Building docker image

```bash

    docker build -t <imagename:version> .

```



# Running docker container


```bash

    // 9006 port is given since the docker file contains 9005 port
    docker run -it -d -p <outside-port-of-your-choice>:9006 <imagename:version>

```


