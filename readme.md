## RabbitMQ Tutorial Code

This is the sample code from [https://www.rabbitmq.com/tutorials/tutorial-one-go.html](https://www.rabbitmq.com/tutorials/tutorial-one-go.html)

There is one small but significant change, the [worker.go](https://github.com/rabbitmq/rabbitmq-tutorials/blob/master/go/worker.go) on GitHub as the Ack before the work is complete, the [worker.go](pub_sub/worker.go) in this repo asend the Ack post processing.