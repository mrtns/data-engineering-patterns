# data-engineering

## Patterns

* ES Streams  
  https://streams.spec.whatwg.org/
  
* ES Observables  
  https://github.com/tc39/proposal-observable

* ES Async Iterators
  https://github.com/tc39/proposal-async-iteration
  
  * http://2ality.com/2016/10/asynchronous-iteration.html
  
  * [Why Async Iterators Matter](https://docs.google.com/presentation/d/1r2V1sLG8JSSk8txiLh4wfTkom-BoOsk52FgPBy8o3RM/edit?usp=sharing)
  
    ![](https://pbs.twimg.com/media/DUyiW_8X0AAadXm.jpg:large)


## Topics

### Streams vs Observables

* https://github.com/whatwg/streams/blob/master/FAQ.md  
  > Observables/EventTarget are specifically designed for multi-consumer scenarios, and have no support for backpressure.

  > Observables and readable streams both share the semantic of "zero or more chunks, followed by either an error or done signal". But beyond that, they are not very comparable.
