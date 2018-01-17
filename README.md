# Simple RabbitMQ Manager API PHP Client

This library is intended to help management of RabbitMQ server in an PHP application.

```php
$client = new \RabbitMqHttpApiClient('localhost', 15672, 'login', 'password');
$queueInfo = $client->queueInfo('\', 'queueName');
```
