## Spring Cloud Gateway Advanced Demo Project  [![Twitter](https://img.shields.io/twitter/follow/piotr_minkowski.svg?style=social&logo=twitter&label=Follow%20Me)](https://twitter.com/piotr_minkowski)

<img src="https://piotrminkowski.files.wordpress.com/2019/11/rate-limiter-logo.png" title="Rate" width="120" height="60"><br/>

In this project I'm demonstrating you the most interesting features of [Spring Cloud Gateway](https://cloud.spring.io/spring-cloud-gateway/reference/html/)

Currently you may find here examples of: 
1. Redis-based **Request Rate Limiter** - the detailed description may be found in the article on my blog [Rate Limiting In Spring Cloud Gateway With Redis](https://piotrminkowski.wordpress.com/2019/11/15/rate-limiting-in-spring-cloud-gateway-with-redis/)
2. Circuit Breaker and Fallback with [resilience4j](https://resilience4j.readme.io/docs/getting-started) - coming soon :)

### Usage 
1. To build and run the main application you need to have Maven, JDK11+ and Docker.
2. To build it run command `mvn clean install`
3. During Maven build the JUnit integration tests are running. They are using [Testcontainers](https://www.testcontainers.org/) for mocking downstream service and third-party tools like Redis.

Feel free to propose your examples or suggestions !
