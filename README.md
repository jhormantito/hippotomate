# Hippotomate &middot; ![CircleCI Status](https://circleci.com/gh/MihaiValentin/hippotomate.svg?style=shield&circle-token=3e97efa241fd2343b3a3317c197cfc7b63f39c9a)

Hippotomate is a tool for Selenium that will provide valuable insights in your automated tests and present them in a meaningful and concise way.

*Core features:*
* View screenshots, page source and other insights on the spot
* Run your tests step by step
* Log data from the tests and analyze them with ease
* Get a high-level friendly view, or deep dive into technical details
* Programming language agnostic

Hippotomate is currently a proof of concept and its purpose is to validate the usefulness of such tools for QA engineers. Therefore, except some rough edges :)

For more information, check [How to use guide](HOW-TO-USE.md) and [www.hippotomate.com](http://www.hippotomate.com)

## How to develop Hippotomate

* `npm install`
* `npm run env`

## Build app packages

* `npm install`
* `npm run build-package-current` to output the app for the current platform (OS) you're on ( in target/ folder)
* `npm run build-package-all` to output the apps for all the available platforms (OS)
