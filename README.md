[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Faccidentalmeme%2FWebClient-1.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Faccidentalmeme%2FWebClient-1?ref=badge_shield)

ProtonMail Web Client
=======

Official AngularJS web client for the [ProtonMail secure email service](https://protonmail.com). ProtonMail also makes use of [OpenPGPjs](https://github.com/openpgpjs/openpgpjs) as our message crytography is PGP compliant.

### Translations

To assist with the ProtonMail Translation Project, please visit our dedicated translation repository: [translations repository](https://github.com/ProtonMail/translations).

### Basic Installation

#### If you have node >= 0.12 installed locally

- `npm install` (requires nodejs)
- `npm start` to start the app locally at `http://localhost:8080`

#### If you have docker, and prefer to not install node (or anything else) locally

- `make start` to start the app on a container (use `make localurl` to find the url where it's running)
- `make test` to build the app (actual tests are still to come)

There is a very good chance you won't be able to use the app locally because of various security headers and such. But you should be able to get the code running enough to poke around and inspect it.

We are still in Beta and will have a more refined build process, installation instructions, unit tests, and all that good stuff once we exit Beta.

### Development

We are very open to bug reports via Issues as well as Pull Requests.

### End to end testing for AngularJS

Installation:

```shell
npm install -g protractor
webdriver-manager update
```

Start up a Selenium Server:

```shell
webdriver-manager start
```

Run tests:

```shell
protractor protractor_conf.js
```

Run a scenario:

```shell
protractor protractor_conf.js --suite=login
```

### License

Copyright (c) 2013-2016

Proton Technologies A.G. (Switzerland)

Email: contact@protonmail.ch

License: https://github.com/ProtonMail/WebClient/blob/master/license.md


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Faccidentalmeme%2FWebClient-1.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Faccidentalmeme%2FWebClient-1?ref=badge_large)