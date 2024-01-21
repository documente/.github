<p align="center">
    <a href="https://github.com/documente/documente">
        <img alt="Logo for the Documenté literate testing framework" src="https://github.com/documente/documente.github.io/raw/main/public/logo.svg" title="Documenté logo" width="200"/>
    </a>
</p>

<h3 align="center">Welcome to Documenté</h3>

<p align="center">
The Javascript literate testing framework
</p>

## What is Documenté?

Documenté is a literate testing framework that allows you to generate automated tests from user documentation.

It integrates into test frameworks such as [Cypress](https://www.cypress.io/) or [Playwright](https://playwright.dev/), and builds on concepts from [Behaviour-Driven-Development](https://en.wikipedia.org/wiki/Behavior-driven_development) and [literate programming](https://en.wikipedia.org/wiki/Literate_programming).

##  Why Documenté?

Automated testing is a key component of modern software development.
It allows to ensure that the software behaves as expected and to detect regressions.

However, writing and maintaining automated tests can be a tedious and time-consuming task.
This is especially true for end-to-end tests, which are often written in a way that is not very readable and not very maintainable.

Documenté aims to solve this problem by providing a framework that allows to write automated tests
in an almost natural language called [Phrasé](https://github.com/documente/documente/tree/main/packages/phrase), using a syntax that is very close to the one used in BDD (Behaviour-Driven-Development).

Tests written with [Phrasé](https://github.com/documente/documente/tree/main/packages/phrase) are meant to be included in the documentation of the application.
This allows to keep the documentation and the tests in sync, and to make the tests more accessible to non-technical people.

Regressions are easier to detect, as the tests are written in a way that is closer to the way the application is used.

Specification issues are also easier to spot and fix, as they are located in the same place as the tests.

## How does it work?

Documenté reads markdown files containing Phrasé specifications and generates tests from them.
The generated tests are then executed by your test runner of choice.

Documenté can be launched from the command line, from its programmatic API, or can be integrated in a CI/CD pipeline.

You can also skip the test extraction and directly write your tests with Phrasé inside your favorite automated test framework.

You can refer to the [kitchen sink application](https://documente.github.io/kitchen-sink) to get an overview of Documenté testing capabilities.

The [example project](https://github.com/documente/example-sut) will also give you a good idea of how to write specifications.

## Getting started

Refer to the [Documenté website](https://documente.github.io/) for more information.

## Repositories overview

Here is an overview of the different repositories you'll find in this organization :
- [documente](https://github.com/documente/documente): the core monorepo, including Phrasé language, tooling to generate and run tests, and example projects
- [example-sut](https://github.com/documente/example-sut): a demo application along with its documentation to showcase Documenté features and its integration into CI/CD pipelines
- [phrase-checker](https://github.com/documente/phrase-checker): a web application to check Phrasé syntax

## Contribute

To date, Documented is a solo initiative. I would be delighted to involve contributors in this endeavor, whether it's contributing to the framework's design, testing and suggesting modifications, or participating in the implementation. If you're interested, feel free to contact me at the following email address: pc.kerneis[at]gmail[dot]com.
