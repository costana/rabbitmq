# Subindo container RabbitMQ no docker-compose

## Setup
```
git clone https://github.com/costana/rabbitmq.git
cd rabbitmq
docker-compose up

```

## Play
```
cd examples/Receive
dotnet run

cd examples/Send
dotnet run
```
Acesso ao Management UI: http://localhost:15672 

Use os dados de acesso

```
username: tico
password: tico123
```
