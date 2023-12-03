# Documenté

Documenté is a framework for writing executable specifications for web applications.

It is based on [Cypress](https://www.cypress.io/) and builds on concepts from Behaviour-Driven-Development and literate programming.

##  Why Documenté?

Automated testing is a key component of modern software development.
It allows to ensure that the software behaves as expected and to detect regressions.

However, writing and maintaining automated tests can be a tedious and time-consuming task.
This is especially true for end-to-end tests, which are often written in a way that is not very readable and not very maintainable.

Documenté aims to solve this problem by providing a framework that allows to write automated tests
in an almost natural language called [Phrasé](https://github.com/documente/phrase), using a syntax that is very close to the one used in BDD (Behaviour-Driven-Development).

Tests written with [Phrasé](https://github.com/documente/phrase) are meant to be included in the documentation of the application.
This allows to keep the documentation and the tests in sync, and to make the tests more accessible to non-technical people.

Regressions are easier to detect, as the tests are written in a way that is closer to the way the application is used.

Specification issues are also easier to spot and fix, as they are located in the same place as the tests.

## How does it work?

Documenté reads markdown files containing Phrasé specifications and generates [Cypress](https://www.cypress.io/) tests from them.
The generated tests are then executed by Cypress.

Documenté can be launched from the command line, from its programmatic API, or can be integrated in a CI/CD pipeline.

## Getting started

Refer to the [Documenté repository](https://github.com/documente/documente) for more information.