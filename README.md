# Publicar y Consumir Tópicos de RabbitMQ con Node JS

### Basado en:

(Con correcciones y algunos detalles mas)

* Get Started RabbitMQ Node JS:

https://www.rabbitmq.com/tutorials/tutorial-five-javascript.html


### Ver Repo con el Receptor en:

* https://github.com/diegochavezcarro/node-rabbit-topic-receive 

Se levanta Rabbit con Docker, si no se tiene Docker instalarlo previamente (https://docs.docker.com/install/). Luego:

docker run -d --hostname rabbitmq --name rabbitmq -p 15672:15672 -p 5672:5672 rabbitmq:3.7.14-management

En http://localhost:15672/ se puede ver la consola, acceder con guest/guest