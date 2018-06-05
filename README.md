**VHL QA Automation** is an functional testing framework that can be used to test VHL Sample Application.

# VHL Central
* **QA** -  https://www-1.qa2.vhlcentral.com#

## Getting started

#### Pre-requisites
1. [Download](http://www.oracle.com/technetwork/java/javase/downloads/index.html) Java SDK (min Java7)
2. [Download](https://nodejs.org/en/download/) NodeJS

#### Installation
1. `$ git clone https://github.com/*<vhl-qa-automation-repo-name>*`
2. `$ npm install`

#### Test Execution
1. **Environment Variables**
    1. *VHL_CENTRAL_TEST_ENVIRONMENT*: VHL Application Environment that needs to be tested.
        1. Possible Values: 'qa' |'staging' |'production'
        2. Default value: 'qa'
2. Run test
```sh
$ npm test
```
