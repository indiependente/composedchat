# composedchat
A simple container based chat made with Node.js, Hapi, Socket.io and Redis

## Description
This project is just an example of how to set up a container based application.
I wanted to play with docker and docker-compose, so I choose to split an existing redis/node.js chat into a multi-container application.
The app is made of two containers:
 - web: the webapp itself
 - redis: the redis in-memory db

The containers are tied together by docker-compose as described in the docker-compose.yml file.

## Prerequisites
 - Docker https://docs.docker.com/engine/installation/
 - Docker compose https://docs.docker.com/compose/install/

## Installation
 - `git clone https://github.com/indiependente/composedchat.git`
 - `docker-compose up`
 - Enjoy!

Feel free to fork and send pull requests!
