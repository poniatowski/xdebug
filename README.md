
RabbitMQ
```mermaid
graph TD;
SQS-->SES;
SQS-->ExceptionHander;
SES-->Lambda;
Lambda-->Festicket;
```
