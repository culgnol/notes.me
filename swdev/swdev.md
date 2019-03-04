# Software Development

SDLC
Foundation
* Design
* Implementation
* Testing
* Maintenance


Testing at every phase
* Requirement Analysis -> Acceptance(+Regression) Testing
* High Level Design -> System Testing
* Low Level Design -> Integration Testing
* Coding -> Unit Testing


Types of Acceptance Testing
* user-based
* business-based
* alpha/beta
* E2E

http://www.getlaura.com/testing-unit-vs-integration-vs-regression-vs-acceptance/
https://www.guru99.com/regression-testing.html
https://smartbear.com/learn/automated-testing/what-is-regression-testing/
https://smartbear.com/learn/automated-testing/software-testing-methodologies/

---
UI Testing Pyramid

UI, Testing the end result in the browser

Integration, (i.e. testing how our Vue components work together)

Unit, (i.e. testing our individual Vue component)

---
API Testing Pyramid


E2E, User/Persona (use cases E2E; microservice to microservice)

Integration, Validate communication paths (microservice to infrastructure)

Contract, PACT(https://docs.pact.io/) tests,
* https://www.mabl.com/blog/understanding-contract-testing-microservices-mabl
* https://medium.com/@m_arlandy/contract-testing-for-microservices-using-swagger-prism-and-dredd-efdd463b9433
* https://www.infoq.com/articles/contract-testing-spring-cloud-contract
* https://spring.io/guides/gs/contract-rest/
* https://hackernoon.com/api-consumer-contract-tests-and-test-doubles-with-karate-72c30ea25c18
* https://www.youtube.com/watch?

Component, Testing microservice in isolation (test server in memory; stub out other microservice dependencies

Unit/Functional

---
Test Infrastructure/Stack

||Everywhere|UI|API|
|---|---|---|---|
|Browsers| |Full Browser (GUI): Chrome, Firefox, IE; Headless (no GUI): Chrome, Firefox, PhantomJS; Others: Zombie.js, Slimer.js| |
|Test Runner|Karma, https://github.com/smeyn/gallio-testlink-adapter/wiki/The-Gallio-Automation-Platform| | |
|Framework|Mocha, xUnit, NUnit| | |
|Assertion Library|Chai| | |
|Mocks|Sinon, JMock| | |
|All inclusive frameworks|Jasmine, Jest, AVA| | |

Javascript Testing Combo
* Vuejs: Karma, Mocha, Chai, Sinon
* Angular: Protractor, Jasmine...

---

[\[:house:\]](../README.md)