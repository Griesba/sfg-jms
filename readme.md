

JMS is transactional: in case of exception in client and message received is not confirmed, the message will be re-queued.

- running ActiveMQ docker image. Instruction in page: https://github.com/vromero/activemq-artemis-docker

* run command <docker run -it --rm -p 8161:8161 -p 61616:61616 vromero/activemq-artemis>
* one the container is up, connect to using docker-machine ip and creation port. On window 192.168.99.102:8186 (to get ip run <docker-machine ip> command)
* login and password are in the activemq-artemis-docker github page (artemis / simetraehcapa) 