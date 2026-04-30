# Message Queues

## What are Message Queues?

* Message Queues are basically a communication system that allows system components to send messages to each other in an asynchronous manner
* It acts as a mediator that temporarily stores the messages sent by the sender (producer) to the receiver (consumer)

## Why are they used?

1. Decoupling Systems

   * A service (producer) can send a message without having to wait for the receiver (consumer)
   * Makes systems easier to maintain and scale

2. Asynchronous Processing

   * If there are any tasks available, they can be finished at a later time
   * Hence the main application stays fast, since they do not have to wait for any task to be completed
  
3. Load Balancing

   * If there are many messages received, multiple consumers can process them in parallel
  
4. Reliability and Fault Tolerance

   * Messages are basically stored until they are processed successfully
   * Meaning if there are any service crashes, the messages are not lost at all
  
## What are popular tools?

* RabbitMQ
* Apache Kafka
* Amazon SQS
* Google Cloud Pub/Sub
* Redis Streams
* ActiveMq

## What is Enterprise Message Bus?

* Also called Enterprise Service Bus (ESB)
* It is a software architecture which acts as a centralized middleware
* Helps in mediating communication between applications that were not originally designed to work together


## References

* https://www.geeksforgeeks.org/system-design/message-queues-system-design/
* https://medium.com/must-know-computer-science/system-design-message-queues-245612428a22
* https://blog.algomaster.io/p/message-queues
* https://www.confluent.io/learn/enterprise-service-bus/
