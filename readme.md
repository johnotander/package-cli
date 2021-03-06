# package-cli [![Build Status](https://secure.travis-ci.org/package-css/package-cli.png?branch=master)](https://travis-ci.org/package-css/package-cli) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

__Work in progress__.

This missing CLI tool for your `package.json`.

## Installation

```bash
npm install --g package-cli
```

## Usage

```sh
$ package -h

  The missing package.json CLI tool

  Usage
    $ package -h

  Options
    -r, --remove Remove a key
    -a, --add Add a key

  Example
    $ package --add=awesome:value
    $ package --remove=awesome
```

## TODO

- [ ] Sort keys (https://github.com/npm/normalize-package-data)
- [ ] Add support for arrays or multiple add/removes
- [ ] Add tests

## License

MIT

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Crafted with <3 by John Otander ([@4lpine](https://twitter.com/4lpine)).

***

> This package was initially generated with [yeoman](http://yeoman.io) and the [p generator](https://github.com/johnotander/generator-p.git).
