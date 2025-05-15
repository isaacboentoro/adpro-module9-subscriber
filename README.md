> 1. What is amqp?
AMQP is an open standard application layer protocol for message middleware. It enables applications to communicate by sending messages regardless of programming language, operating system, or cloud providers.

> 2. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for? 

This is a connection string for an amqp server. `guest` is the username for authentication, second `guest` is the password, `localhost` is the host or server address, `5672` is the default port numbe that amqp servers listen on. 

### Slow subscriber simulation
![busy server](<images/busy server.png>)
The total queue is 4 because I ran publisher 4 times in quick succession and subscriber needs time to process those messages.
