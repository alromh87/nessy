# Nessy [![License][LicenseIMGURL]][LicenseURL] [![NPM version][NPMIMGURL]][NPMURL] [![Dependency Status][DependencyStatusIMGURL]][DependencyStatusURL] [![Build Status][BuildStatusIMGURL]][BuildStatusURL] [![Coverage Status][CoverageIMGURL]][CoverageURL]

Set value in nested object.

## Install

`npm i nessy --save`

## Hot to use?

```js
var nessy = require('nessy');

nessy('hello.world', 'why not?', {
    hello: {
        world: {
            'could be used in browser as well'
        }
    }
});

// returns
{
    hello: {
        world: {
            'why not?'
        }
    }
}
```

## Environments

In old `node.js` environments that not fully supports `es2015`, `nessy` could be used with:

```js
var nessy = require('nessy/legacy');
```

## Related

- [jessy](https://github.com/coderaiser/jessy "jessy") - get value by object property.
- [all-object-keys](https://github.com/coderaiser/all-object-keys "all-object-keys") - get all keys of object.

## License

MIT

[NPMIMGURL]:                https://img.shields.io/npm/v/nessy.svg?style=flat
[BuildStatusIMGURL]:        https://img.shields.io/travis/coderaiser/nessy/master.svg?style=flat
[DependencyStatusIMGURL]:   https://img.shields.io/gemnasium/coderaiser/nessy.svg?style=flat
[LicenseIMGURL]:            https://img.shields.io/badge/license-MIT-317BF9.svg?style=flat
[NPMURL]:                   https://npmjs.org/package/nessy "npm"
[BuildStatusURL]:           https://travis-ci.org/coderaiser/nessy  "Build Status"
[DependencyStatusURL]:      https://gemnasium.com/coderaiser/nessy "Dependency Status"
[LicenseURL]:               https://tldrlegal.com/license/mit-license "MIT License"

[CoverageURL]:              https://coveralls.io/github/coderaiser/nessy?branch=master
[CoverageIMGURL]:           https://coveralls.io/repos/coderaiser/nessy/badge.svg?branch=master&service=github
