This projects follows the tutorial on []().

It assumes that:
> ... RabbitMQ is installed and running on localhost on the standard port (5672) ...

This can be set up with docker
```shell
$ docker run --name rabbitmq-tutorial -d --hostname rabbitmq -e RABBITMQ_PLUGINS=rabbitmq_management,rabbitmq_event_exchange -p 5672:5672 -p 15672:15672 bitnami/rabbitmq:3.11.5-debian-11-r0
```