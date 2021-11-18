# Scalable Websocket 
this repo is the thinking of how to design a scalable websocket service

![Imgur](https://imgur.com/xETCAa2.jpg)

in above diagram, each node in our system should be scalable,

load balancer is scalable

websocket is scalable

message queue is scalable

database is scalable

in this study, we use the message queue to be the buffer of DB and DB client

thus, DB might not be the bottleneck of this system.

we focus on LB, Websocket, message Queue cooperation, how it work to build a scalable service.

## Load Balacer

## WebSocket

## Message Queue






## Reference
- https://www.confluent.io/blog/kafka-client-cannot-connect-to-broker-on-aws-on-docker-etc/
- https://github.com/Eficode/wait-for
- https://stackoverflow.com/questions/40454470/how-can-i-use-a-variable-inside-a-dockerfile-cmd
- https://www.nginx.com/blog/websocket-nginx/
- https://github.com/tingyuchang/go-ws
