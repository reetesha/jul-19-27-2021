* Reactive programming
* Asynchronous and Non blocking way of giving out data
* New paradigm
* Push model of data

### Traditional API design

* Blocking and Synchronous
* send a request to a service; service calls DB; you wait for the response
* If data is huge, you won't be able to handle the volume or not equipped to handle the large volume
* Futures, callbacks, CompletableFuture;
* They have their own share of problems; Multiple async calls; Error handling; readability of code
* Latency or response time is still not very fast

### Reactive programming

* Asynchronous and Non blocking
* Subscribe to the DATA SOURCE; 
* And start receiving data
* Close or cancel the subscription anytime you want
* Data is pushed to you in a typical event/message-driven mechanism  

* Reactive streams specification https://github.com/reactive-streams/reactive-streams-jvm
* RxJava, Project Reactor, Flow (Jdk 9), Vert.x
* RxJava 3