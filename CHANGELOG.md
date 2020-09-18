# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [2.1.3](https://github.com/hpcc-systems/vscode-ecl/compare/v1.9.5...v2.1.3) (2020-09-18)


### Bug Fixes

* **build:**  Rollback to candidate-1.x ([de4ed38](https://github.com/hpcc-systems/vscode-ecl/commit/de4ed38099bed3530837685710d5bec264a0228d))

### [1.9.5](https://github.com/hpcc-systems/vscode-ecl/compare/v1.9.4...v1.9.5) (2020-05-11)


### Bug Fixes

* **KEL:** Improve syntax lexing ([34e7d03](https://github.com/hpcc-systems/vscode-ecl/commit/34e7d0302632e92100492a63e5f22202e0f5944f))

### [1.9.4](https://github.com/hpcc-systems/vscode-ecl/compare/v1.9.3...v1.9.4) (2020-04-29)


### Bug Fixes

* **DebugSession:** Workaround VSCode regression ([2ae0b45](https://github.com/hpcc-systems/vscode-ecl/commit/2ae0b45886eaec5d6564156217e1c0c9153860ee)), closes [#177](https://github.com/hpcc-systems/vscode-ecl/issues/177)

### [1.9.3](https://github.com/hpcc-systems/vscode-ecl/compare/v1.9.2...v1.9.3) (2020-04-29)


### Bug Fixes

* **DebugSession:** Enable debug logging ([be0e785](https://github.com/hpcc-systems/vscode-ecl/commit/be0e7856581f7da910b170592058ff0f673336b7))

### [1.9.2](https://github.com/hpcc-systems/vscode-ecl/compare/v1.9.1...v1.9.2) (2020-04-24)


### Bug Fixes

* **KEL:** Check syntax was throwing away the errors. ([a6aeb9a](https://github.com/hpcc-systems/vscode-ecl/commit/a6aeb9a67e0985791474c1171ac974052973bd29))

### [1.9.1](https://github.com/hpcc-systems/vscode-ecl/compare/v1.9.0...v1.9.1) (2020-04-24)


### Bug Fixes

* **README.md:** Add information for KEL ([a92f1e8](https://github.com/hpcc-systems/vscode-ecl/commit/a92f1e842c0130818fe4c438bdd95f043e998955))

## [1.9.0](https://github.com/hpcc-systems/vscode-ecl/compare/v1.8.0...v1.9.0) (2020-04-24)


### Features

* **KEL:** Add initial KEL support ([c4cf428](https://github.com/hpcc-systems/vscode-ecl/commit/c4cf4289f289837695b23ba6affbae0161689776))

## [1.8.0](https://github.com/hpcc-systems/vscode-ecl/compare/v1.7.1...v1.8.0) (2020-04-21)


### Features

* **snippets:**  Enhanced Snippets ([7b30368](https://github.com/hpcc-systems/vscode-ecl/commit/7b30368bf7a4c8617cb9b6b812d9eac7df428aac))

### [1.7.1](https://github.com/hpcc-systems/vscode-ecl/compare/v1.7.0...v1.7.1) (2020-04-09)


### Bug Fixes

* **WUUpdate:** Add retry and extra logging. ([c53a6d1](https://github.com/hpcc-systems/vscode-ecl/commit/c53a6d1e797872ea071744b62b475024fdd957bd))

## [1.7.0](https://github.com/hpcc-systems/vscode-ecl/compare/v1.6.0...v1.7.0) (2020-04-07)


### Features

* **comms:** Add timeout option ([a65ae4f](https://github.com/hpcc-systems/vscode-ecl/commit/a65ae4f79f45e9551b52b2114ed08a21e3cd1ae7))

## [1.6.0](https://github.com/hpcc-systems/vscode-ecl/compare/v1.0.2...v1.6.0) (2020-03-31)


### Features

* **build:** Bundle extension ([8d6074e](https://github.com/hpcc-systems/vscode-ecl/commit/8d6074e1b9a2a482ce76fe8ff582ad99a6847043))
* **ClientTools:** Add quick select specific eclcc version ([0810aa4](https://github.com/hpcc-systems/vscode-ecl/commit/0810aa4418115fc91fe236bf409dd6afa775141b))
* **omd:** Add initial support for ObservableMD documents ([4e00f2b](https://github.com/hpcc-systems/vscode-ecl/commit/4e00f2b7fad94f4ee2d6d8f44f8b92ada0d354d2))
* **Overview:** Add document symbol support from meta information ([dffb514](https://github.com/hpcc-systems/vscode-ecl/commit/dffb51470c433565af3074dcd18a4db6808800c1))
* **terminal:** Add command to open ECL Terminal ([6f6e1d3](https://github.com/hpcc-systems/vscode-ecl/commit/6f6e1d32ba3252739db8902a25023e11d7e7510b))
* **terminal:** Add command to open ECL Terminal ([5281c58](https://github.com/hpcc-systems/vscode-ecl/commit/5281c5817ba59db8d5c0eafb0682a5a66745ef99))
* Add "publish" action ([d7bd786](https://github.com/hpcc-systems/vscode-ecl/commit/d7bd786247e5b7e3f8b67e8a4445edbae80b0a04))
* Support XML archive submissions ([162389d](https://github.com/hpcc-systems/vscode-ecl/commit/162389d5064e784a360dee25f9d5abf2c8e56908))


### Bug Fixes

* **build:** Add missing dependency "tmp" ([8c2fdf3](https://github.com/hpcc-systems/vscode-ecl/commit/8c2fdf32dee74e7d3b052d05865c97afe92c413b))
* **comms:** "rejectUnauthorized" was not being honoured ([91349f5](https://github.com/hpcc-systems/vscode-ecl/commit/91349f5a4bd8552e74415a450a5c31f10d735684))
* **config:** Ubuntu fails to retrieve config setting ([7d557e8](https://github.com/hpcc-systems/vscode-ecl/commit/7d557e8f445a096f72c1a9cf0ed7199f66f4e425))
* **credentials:** Credential prompt fails ([58acb39](https://github.com/hpcc-systems/vscode-ecl/commit/58acb393c2a7ff36d34fd23167ed8356872d39a6))
* **package:** Update default icon ([2bffd6b](https://github.com/hpcc-systems/vscode-ecl/commit/2bffd6be0ee8470b03de22972cde8af847be0dc7))
* **problems:** Error parse failed when path contained a space. ([bcdd5bf](https://github.com/hpcc-systems/vscode-ecl/commit/bcdd5bf95a37c6c1065344bd7b245ac7addfa400))
* **publish:** Add (R) to company name ([bc86ca3](https://github.com/hpcc-systems/vscode-ecl/commit/bc86ca349befd4a4ff8037687e5c2e0a2eea960d))
*  Missing comms dependency ([bbd7ba0](https://github.com/hpcc-systems/vscode-ecl/commit/bbd7ba08ec73bfba45d28582ab7901f35e151d6b))
* Invalid hot key mapping ([904a8f3](https://github.com/hpcc-systems/vscode-ecl/commit/904a8f36931c9fb016864296aba7c89176deb325))

### [1.5.1](https://github.com/hpcc-systems/vscode-ecl/compare/v1.5.0...v1.5.1) (2020-03-20)

## [1.5.0](https://github.com/hpcc-systems/vscode-ecl/compare/v1.4.1...v1.5.0) (2020-01-23)


### Features

* **terminal:** Add command to open ECL Terminal ([6f6e1d3](https://github.com/hpcc-systems/vscode-ecl/commit/6f6e1d32ba3252739db8902a25023e11d7e7510b))
* **terminal:** Add command to open ECL Terminal ([5281c58](https://github.com/hpcc-systems/vscode-ecl/commit/5281c5817ba59db8d5c0eafb0682a5a66745ef99))

### [1.4.1](https://github.com/hpcc-systems/vscode-ecl/compare/v1.4.0...v1.4.1) (2020-01-10)

## [1.4.0](https://github.com/hpcc-systems/vscode-ecl/compare/v1.3.0...v1.4.0) (2020-01-10)


### Features

* **ClientTools:** Add quick select specific eclcc version ([0810aa4](https://github.com/hpcc-systems/vscode-ecl/commit/0810aa4418115fc91fe236bf409dd6afa775141b))

## [1.3.0](https://github.com/hpcc-systems/vscode-ecl/compare/v1.2.1...v1.3.0) (2019-10-11)


### Features

* Add "publish" action ([d7bd786](https://github.com/hpcc-systems/vscode-ecl/commit/d7bd786247e5b7e3f8b67e8a4445edbae80b0a04))

### [1.2.1](https://github.com/hpcc-systems/vscode-ecl/compare/v1.2.0...v1.2.1) (2019-10-10)

## [1.2.0](https://github.com/hpcc-systems/vscode-ecl/compare/v1.1.5...v1.2.0) (2019-10-10)


### Features

* **build:** Bundle extension ([8d6074e](https://github.com/hpcc-systems/vscode-ecl/commit/8d6074e1b9a2a482ce76fe8ff582ad99a6847043))

## [1.1.5](https://github.com/hpcc-systems/vscode-ecl/compare/v1.1.4...v1.1.5) (2019-09-10)



## [1.1.4](https://github.com/hpcc-systems/vscode-ecl/compare/v1.1.2...v1.1.4) (2019-09-09)



## [1.1.2](https://github.com/hpcc-systems/vscode-ecl/compare/v1.1.1...v1.1.2) (2019-09-09)


### Bug Fixes

* **package:** Update default icon ([2bffd6b](https://github.com/hpcc-systems/vscode-ecl/commit/2bffd6b))
* **problems:** Error parse failed when path contained a space. ([bcdd5bf](https://github.com/hpcc-systems/vscode-ecl/commit/bcdd5bf))
* **publish:** Add (R) to company name ([bc86ca3](https://github.com/hpcc-systems/vscode-ecl/commit/bc86ca3))



## [1.1.1](https://github.com/hpcc-systems/vscode-ecl/compare/v1.1.0...v1.1.1) (2019-03-29)


### Bug Fixes

* **build:** Add missing dependency "tmp" ([8c2fdf3](https://github.com/hpcc-systems/vscode-ecl/commit/8c2fdf3))



# [1.1.0](https://github.com/hpcc-systems/vscode-ecl/compare/v1.0.12...v1.1.0) (2019-03-29)


### Bug Fixes

* **comms:** "rejectUnauthorized" was not being honoured ([91349f5](https://github.com/hpcc-systems/vscode-ecl/commit/91349f5))


### Features

* Support XML archive submissions ([162389d](https://github.com/hpcc-systems/vscode-ecl/commit/162389d))
* **Overview:** Add document symbol support from meta information ([dffb514](https://github.com/hpcc-systems/vscode-ecl/commit/dffb514))



<a name="1.0.12"></a>
## [1.0.12](https://github.com/hpcc-systems/vscode-ecl/compare/v1.0.11...v1.0.12) (2019-01-02)



<a name="1.0.11"></a>
## [1.0.11](https://github.com/hpcc-systems/vscode-ecl/compare/v1.0.10...v1.0.11) (2019-01-02)



<a name="1.0.10"></a>
## [1.0.10](https://github.com/hpcc-systems/vscode-ecl/compare/v1.0.9...v1.0.10) (2018-11-19)


### Bug Fixes

*  Missing comms dependency ([bbd7ba0](https://github.com/hpcc-systems/vscode-ecl/commit/bbd7ba0))



<a name="1.0.9"></a>
## [1.0.9](https://github.com/hpcc-systems/vscode-ecl/compare/v1.0.8...v1.0.9) (2018-11-13)



<a name="1.0.9"></a>
## [1.0.9](https://github.com/hpcc-systems/vscode-ecl/compare/v1.0.8...v1.0.9) (2018-11-13)



# ECL for Visual Studio Code

Read the [Offical Release Notes](https://github.com/GordonSmith/vscode-ecl/releases) to know what has changed over the last few versions of this extension
