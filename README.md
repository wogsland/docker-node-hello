# Node.js Hello World

Node.js Hello World on CentOS using [docker][].

## Prerequisites

- [Node.js & npm][node-js-download]

## Getting Started

-   Build the docker image:

        docker build -t example/docker-node-hello:latest .

-   Start up the container:

        docker run -d -p 8080:8080 example/docker-node-hello:latest

-   Test app using the port in previous step:

        curl localhost:8080

    It should print `Hello World. Wish you were here.` to the console.

## Acknowledgements

Many thanks to @shykes and @unclejack for their support on IRC as well as the
@dotCloud team for docker.


[node-js-download]: http://nodejs.org/download/
[docker]: http://docker.io
