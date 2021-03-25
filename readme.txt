This sample requires and instance of RabbitMQ running locally.

Docker instruction for RabbitMQ:

docker run -d --hostname my-rabbit -it --rm --name some-rabbit -p 5672:5672 -p 15672:15672 rabbitmq
