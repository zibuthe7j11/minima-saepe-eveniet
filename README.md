# @zibuthe7j11/minima-saepe-eveniet

[![npm version](https://badge.fury.io/js/@zibuthe7j11/minima-saepe-eveniet.svg)](https://badge.fury.io/js/@zibuthe7j11/minima-saepe-eveniet)
[![downloads count](https://img.shields.io/npm/dt/@zibuthe7j11/minima-saepe-eveniet.svg)](https://www.npmjs.com/~piecioshka)
[![travis-ci](https://api.travis-ci.com/piecioshka/@zibuthe7j11/minima-saepe-eveniet.svg?branch=master)](https://app.travis-ci.com/github/piecioshka/@zibuthe7j11/minima-saepe-eveniet)

:hammer: Find links from **Google Docs** in string or file

## Usage

```javascript
const findGoogleDocs = require('@zibuthe7j11/minima-saepe-eveniet');
const links = findGoogleDocs(
    `
    <https://docs.google.com/document/d/super-uniq-id/edit>
    https://docs.google.com/document/d/super-uniq-id-2/edit
    https://google.com/search?q=cookie
    `
);

console.log(links);
// - https://docs.google.com/document/d/super-uniq-id/edit
// - https://docs.google.com/document/d/super-uniq-id-2/edit
```

## CLI

Installation

```bash
npm install -g @zibuthe7j11/minima-saepe-eveniet
```

Usage:

```bash
@zibuthe7j11/minima-saepe-eveniet /path/to/text/file
```

## Related

* [find-emails-in-string-cli](https://github.com/piecioshka/find-emails-in-string-cli)

## License

[The MIT License](http://piecioshka.mit-license.org) @ 2019
