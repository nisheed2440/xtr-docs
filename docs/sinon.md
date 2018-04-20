# SinonJS

## Quadrant
ubiquitous

## Type
frameworks

## Description
Sinon is a Standalone test spies, stubs and mocks for JavaScript. It works with any unit testing framework.

## Resources
[SinonJS](http://sinonjs.org/)
[Semaphore](https://semaphoreci.com/community/tutorials/best-practices-for-spies-stubs-and-mocks-in-sinon-js)
[SitePoint](https://www.sitepoint.com/sinon-tutorial-javascript-testing-mocks-spies-stubs/)

``` js
"test should call subscribers on publish": function () {
    var callback = sinon.spy();
    PubSub.subscribe("message", callback);

    PubSub.publishSync("message");

    assertTrue(callback.called);
}
```

## Github
[SinonJS](https://github.com/sinonjs/sinon)

### Platform
web