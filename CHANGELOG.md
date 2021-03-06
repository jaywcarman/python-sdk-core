# [3.3.0](https://github.com/IBM/python-sdk-core/compare/v3.2.0...v3.3.0) (2020-10-07)


### Features

* allow gzip compression on request bodies ([196a407](https://github.com/IBM/python-sdk-core/commit/196a407c40c0c99b2465d19ec8cca1f85b51ee86))

# [3.2.0](https://github.com/IBM/python-sdk-core/compare/v3.1.0...v3.2.0) (2020-09-18)


### Features

* **IAM Authenticator:** add support for optional 'scope' property ([2e776c2](https://github.com/IBM/python-sdk-core/commit/2e776c2ba402c3b2846f5758f64d2776492ae764))

# [3.1.0](https://github.com/IBM/python-sdk-core/compare/v3.0.0...v3.1.0) (2020-06-15)


### Features

* **BaseService:** support stream=True in BaseService.send() ([bf4179b](https://github.com/IBM/python-sdk-core/commit/bf4179b54407c94707b24caeab6c4aeeb67ee3e7))

# [3.0.0](https://github.com/IBM/python-sdk-core/compare/v2.0.5...v3.0.0) (2020-06-01)


### Bug Fixes

* Combine multiple ending slashes to one ([5496948](https://github.com/IBM/python-sdk-core/commit/549694867285c2ba1d77187bfba108543a225e33))


### BREAKING CHANGES

* Fixing the request URL like this will break compatibility with previous generator versions

## [2.0.5](https://github.com/IBM/python-sdk-core/compare/v2.0.4...v2.0.5) (2020-05-29)


### Bug Fixes

* Revert stripping request URL trailing slashes ([09a193c](https://github.com/IBM/python-sdk-core/commit/09a193ce6b4f0b54b027df07d767f29df85ab71c))

## [2.0.4](https://github.com/IBM/python-sdk-core/compare/v2.0.3...v2.0.4) (2020-05-23)


### Bug Fixes

* Revert service_url slash stripping to work with current generated unit tests ([c960b7d](https://github.com/IBM/python-sdk-core/commit/c960b7dc943ac7d8b1bbe748ee7079aa42497504))

## [2.0.3](https://github.com/IBM/python-sdk-core/compare/v2.0.2...v2.0.3) (2020-05-22)


### Bug Fixes

* Don't rstrip slash when service_url is none ([091ecde](https://github.com/IBM/python-sdk-core/commit/091ecde7ab6c8aadc81c71aa35d6a33572856ac8))

## [2.0.2](https://github.com/IBM/python-sdk-core/compare/v2.0.1...v2.0.2) (2020-05-22)


### Bug Fixes

* Strip trailing slash for request url ([47d1d99](https://github.com/IBM/python-sdk-core/commit/47d1d99261767331a2583612ebaf048cf60d1fd3))

## [2.0.1](https://github.com/IBM/python-sdk-core/compare/v2.0.0...v2.0.1) (2020-05-12)


### Bug Fixes

* allow '=' character in environment config values ([8cf4fc9](https://github.com/IBM/python-sdk-core/commit/8cf4fc945a0f77fccf977bfdd0cc3cd203aac0bb))

# [2.0.0](https://github.com/IBM/python-sdk-core/compare/v1.7.3...v2.0.0) (2020-04-10)


### Features

* Add type annotations to parameters and return values ([5d4ef81](https://github.com/IBM/python-sdk-core/commit/5d4ef81a7fa85185839b966b80be6d033bc5eed5))
* Get error status phrase from status code ([d60ae58](https://github.com/IBM/python-sdk-core/commit/d60ae582be18af96c21f1e8a55b707f1d2fa44b4))
* Only override content-type if it is none ([b1177f2](https://github.com/IBM/python-sdk-core/commit/b1177f284a0c08255a5ceea26aca9570c4f699dc))
* Require optional parameters to be keyword-specified ([d9aa1d4](https://github.com/IBM/python-sdk-core/commit/d9aa1d4e4bad68961b3c365aaa8b4d5457921c06))
* Update python super call to newer version ([f038e10](https://github.com/IBM/python-sdk-core/commit/f038e103157afc8ad78d9817b1d233dc507e64db))


### BREAKING CHANGES

* Type annotations new in Python3
* Added super call feature new to Python3
* HTTPStatus is new in Python3
* Keyword-specific optional parameters are new in Python3

## [1.7.3](https://github.com/IBM/python-sdk-core/compare/v1.7.2...v1.7.3) (2020-03-31)


### Bug Fixes

* update classifiers in setup.py ([8b042a8](https://github.com/IBM/python-sdk-core/commit/8b042a831f923f8f09812560f8f0085c7431ce83))

## [1.7.2](https://github.com/IBM/python-sdk-core/compare/v1.7.1...v1.7.2) (2020-03-31)


### Bug Fixes

* update setup.py info for pypi ([1e0d63a](https://github.com/IBM/python-sdk-core/commit/1e0d63aa5b07544b0588fe211dea5b162fe67c49))

## [1.7.1](https://github.com/IBM/python-sdk-core/compare/v1.7.0...v1.7.1) (2020-03-06)


### Bug Fixes

* update README to trigger patch release ([bd389b4](https://github.com/IBM/python-sdk-core/commit/bd389b4e0c4451710c6e12d5325cadcabd6c8289))

# [1.7.0](https://github.com/IBM/python-sdk-core/compare/v1.6.2...v1.7.0) (2020-03-02)


### Features

* Pace requests to token server for new auth tokens ([1dea212](https://github.com/IBM/python-sdk-core/commit/1dea212b8720849370eb8a05d95d74a469a38ab7))

## [1.6.2](https://github.com/IBM/python-sdk-core/compare/v1.6.1...v1.6.2) (2020-02-13)


### Bug Fixes

* Handle conversions for naive datetime values ([f1149fa](https://github.com/IBM/python-sdk-core/commit/f1149fa815f3f1585b3e02da278dd075b9a1f836))

## [1.6.1](https://github.com/IBM/python-sdk-core/compare/v1.6.0...v1.6.1) (2020-02-04)


### Bug Fixes

* Fix date/datetime_to_string handling of non-date/datetime inputs ([8251b82](https://github.com/IBM/python-sdk-core/commit/8251b820e3a00db855d1960defe75279e3b02515))

# [1.6.0](https://github.com/IBM/python-sdk-core/compare/v1.5.2...v1.6.0) (2019-12-19)


### Features

* Add date_to_string and string_to_date utility methods ([6dbfff9](https://github.com/IBM/python-sdk-core/commit/6dbfff92a7758e7cbf78e5cb949dd15beb0dec7f))

## [1.5.2](https://github.com/IBM/python-sdk-core/compare/v1.5.1...v1.5.2) (2019-12-18)


### Bug Fixes

* Update credential file path check to current working directory ([e1ad677](https://github.com/IBM/python-sdk-core/commit/e1ad67781c8bd85739903271deb4ce7a2ea1659a))

## [1.5.1](https://github.com/IBM/python-sdk-core/compare/v1.5.0...v1.5.1) (2019-11-21)


### Bug Fixes

* more semantic-release config changes ([7b20aea](https://github.com/IBM/python-sdk-core/commit/7b20aea08a01df0c5079cb1281c265f31c444d2b))

# [1.5.0](https://github.com/IBM/python-sdk-core/compare/v1.4.0...v1.5.0) (2019-11-21)


### Features

* use new semantic-release config ([040c6a7](https://github.com/IBM/python-sdk-core/commit/040c6a7bb458c109c99e1a9e496b788d24ff12bf))

# [1.4.0](https://github.com/IBM/python-sdk-core/compare/v1.3.0...v1.4.0) (2019-11-20)


### Features

* configure release commit message format ([3d9cbda](https://github.com/IBM/python-sdk-core/commit/3d9cbda0ae2e263d0faf747dac5a99efb090e995))

# [1.3.0](https://github.com/IBM/python-sdk-core/compare/v1.2.0...v1.3.0) (2019-11-20)


### Features

* re-order semrel steps ([525a3fd](https://github.com/IBM/python-sdk-core/commit/525a3fd126a12cb8938c88f89a18f9347394e398))

# [1.2.0](https://github.com/IBM/python-sdk-core/compare/v1.1.3...v1.2.0) (2019-11-20)


### Features

* expand vcap credential loading to support user-defined service names ([32954fa](https://github.com/IBM/python-sdk-core/commit/32954fa1aa6d59416dd4b4c07ea91f51024e7d8f))

## [1.1.3](https://github.com/IBM/python-sdk-core/compare/v1.1.2...v1.1.3) (2019-11-05)


### Bug Fixes

* perform semrel steps in correct order ([545f13e](https://github.com/IBM/python-sdk-core/commit/545f13ebba37578f3cf5f1a7abba28ae159c7faa))

## [1.1.2](https://github.com/IBM/python-sdk-core/compare/v1.1.1...v1.1.2) (2019-11-05)


### Bug Fixes

* updated .buildversion.cfg to trigger patch release ([909196f](https://github.com/IBM/python-sdk-core/commit/909196f2a8e0f24736ee6bf9081b87b7dbcfc499))

## [1.1.1](https://github.com/IBM/python-sdk-core/compare/v1.1.0...v1.1.1) (2019-11-05)


### Bug Fixes

* Fix linting for Python3 and fix all lint issues ([14f2999](https://github.com/IBM/python-sdk-core/commit/14f2999010a9886c20f333247912cbe4996fb662))
