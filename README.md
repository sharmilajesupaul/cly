# @bahmutov/cly

> A prototype of Cypress CLI for quicker project scaffolding

[![NPM][npm-icon]][npm-url]

[![Build status][ci-image]][ci-url]
[![semantic-release][semantic-image]][semantic-url]
[![standard][standard-image]][standard-url]
[![renovate-app badge][renovate-badge]][renovate-app]

## Use

Requires [Node](https://nodejs.org/en/) version 8 or above with `npx` command, assumes you have installed Cypress already with `npm i -D cypress`

```sh
npx @bahmutov/cly init
```

Will output something like the following text on success

```sh
npx: installed 72 in 6.853s
scaffolding new Cypress project
✅ scaffolded "cypress" folder with a single example spec
you can configure additional options in cypress.json file
see https://on.cypress.io/configuration
```

Note: if there are Cypress files or folders already, the `cly` will stop

### Small print

Author: Gleb Bahmutov &lt;gleb.bahmutov@gmail.com&gt; &copy; 2019

* [@bahmutov](https://twitter.com/bahmutov)
* [glebbahmutov.com](https://glebbahmutov.com)
* [blog](https://glebbahmutov.com/blog)

License: MIT - do anything with the code, but don't blame me if it does not work.

Support: if you find any problems with this module, email / tweet /
[open issue](https://github.com/bahmutov/cly/issues) on Github

## MIT License

Copyright (c) 2019 Gleb Bahmutov &lt;gleb.bahmutov@gmail.com&gt;

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

[npm-icon]: https://nodei.co/npm/@bahmutov/cly.svg?downloads=true
[npm-url]: https://npmjs.org/package/@bahmutov/cly
[ci-image]: https://circleci.com/gh/bahmutov/private-module-example-user.svg?style=svg&circle-token=61ab69633676370401cf1373850ef419cb619685
[ci-url]: https://circleci.com/gh/bahmutov/private-module-example-user
[semantic-image]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-url]: https://github.com/semantic-release/semantic-release
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg
[standard-url]: http://standardjs.com/
[renovate-badge]: https://img.shields.io/badge/renovate-app-blue.svg
[renovate-app]: https://renovateapp.com/
