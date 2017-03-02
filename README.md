RxJS WebSocket Example
======================

An example showing how to hook up messages from a WebSocket connection - what is essentially a stream - to RxJS Observables. It uses a Subject to observe changes (WS messages), then proxies those to its Observers. [This Stack Overflow question](http://stackoverflow.com/q/33324227/6860676) explains the issue

Build
-----
1. Run `yarn`
2. Run `gulp`

Page is on localhost:3000