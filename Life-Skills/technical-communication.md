# Messaging Queues

## What are Messaging Queues?

* Message Queues are basically a communication system that allows system components to send messages to each other in an asynchronous manner
* It is a mediator that stores the messages temporarily which was sent by the message sender (producer) to message reciever(consumer)

## Why are they used?

1. Decoupling Systems

   * A service (producer) can send message without having to wait for the reciever (consumer)
   * Makes systems easier to maintain and scale

2. Asynchronous Processing

   * If there are any tasks available, they can be done at a later time
   * Hence the main application stays fast, since they do not have to wait for any task to be completed
  
3. Load Balancing
producer
   * If there are many messages recieved, multiple consumers can process them in parallel
  
4. Reliability and Fault Tolerance

   * Messages are basically stored until they are processed successfully
   * Meaning if there are any service crash, the messages are not lost at all
  
## What are popular tools?

* RabbitMQ
* Apache Kafka
* Amazon SQS
* Google Cloud Pub/Sub
* Redis Streams
* ActiveMq

## What is Enterprise Bus Message?

* Also called as Enterprise Service Bus (ESB)
* It is a software architecture which acts as a centralised middleware
* Helps is cmediating ommunication between applications that was not originally designed to work together


## References

* https://www.geeksforgeeks.org/system-design/message-queues-system-design/
* https://medium.com/must-know-computer-science/system-design-message-queues-245612428a22
* https://blog.algomaster.io/p/message-queues
* https://www.confluent.io/learn/enterprise-service-bus/
