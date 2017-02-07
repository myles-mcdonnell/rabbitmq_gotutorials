## RabbitMQ Tutorial Code

This is the sample code from [https://www.rabbitmq.com/tutorials/tutorial-one-go.html](https://www.rabbitmq.com/tutorials/tutorial-one-go.html)

There is one small but significant change, the [worker.go](https://github.com/rabbitmq/rabbitmq-tutorials/blob/master/go/worker.go) in the RabbitMQ GitHub repo has the Ack before the work is complete, the [worker.go](work_queues/worker.go) in this repo sends the Ack post processing.