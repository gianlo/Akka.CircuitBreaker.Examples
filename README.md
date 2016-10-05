# Akka.CircuitBreaker.Examples
Example use of the CircuitBreaker pattern in Akka

The client WhimsyHttpClient throws exceptions half of the times that it is used.

Modify the WhimsyClientActor to deal with the WhimsyHttpClient throwing exceptions.

Use the Akka provided circuit breaker implementation CircuitBreaker to protect both sync/async calls to the WhimsyHttpClient.

Reference
[http://doc.akka.io/docs/akka/current/common/circuitbreaker.html]
