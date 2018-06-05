# VHL QA Automation

[![VHL Central License](http://img.shields.io/badge/license-VHL%20QA-blue.svg)](https://vistahigherlearning.com/privacy-policy)


**VHL QA Automation** is an functional testing framework that can be used to test VHL Site across a combination of different browsers and platforms.

![VHL Logo](https://assets.maestro.vhlcentral.com/assets/vhl-logo-a7d95265f4cf8ebb5e7ee0098b335e67b3c0e27520adcab6f859cb0e480bbc36.gif)


## Framework Features
* Page Objects
* Different browsers & platforms
* Test execution in cloud
* HTML Test Reports which can be presented to stakeholders
* ...
* <This is phase 1 feature list>


## Framework setup

#### Pre-requisites
1. Git (min version ???). [Download](https://git-scm.com/downloads)
    1. Check git version by executing `$ git --version` in command prompt
2. NodeJS (min version ??) [Download](https://nodejs.org/en/download/)
    1. Check nodejs version by executing `$ node -v` in command prompt

#### Installation
1. Clone Automation Framework [Repo](https://github.com/comprodls/tests-functional.git)
2. Go to clones repo directory
3. Do `$ npm install` to download all dependencies in local

#### Test Execution
1. Run nightwatch test command to execute tests
```sh
$ nightwatch tests\e2e\login.js
```
