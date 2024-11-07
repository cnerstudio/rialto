# Rialto

[![PHP Version](https://img.shields.io/packagist/php-v/cnerstudio/rialto.svg?style=flat-square)](http://php.net/)
[![Composer Version](https://img.shields.io/packagist/v/cnerstudio/rialto.svg?style=flat-square&label=Composer)](https://packagist.org/packages/cnerstudio/rialto)
[![Node Version](https://img.shields.io/node/v/@cnerstudio/rialto.svg?style=flat-square&label=Node)](https://nodejs.org/)
[![NPM Version](https://img.shields.io/npm/v/@cnerstudio/rialto.svg?style=flat-square&label=NPM)](https://www.npmjs.com/package/@cnerstudio/rialto)
[![Build Status](https://img.shields.io/travis/cnerstudio/rialto.svg?style=flat-square&label=Build%20Status)](https://travis-ci.org/cnerstudio/rialto)

A package to manage Node resources from PHP. It can be used to create bridges to interact with Node libraries in PHP, like [PuPHPeteer](https://github.com/cnerstudio/puphpeteer/).

It works by creating a Node process and communicates with it through sockets.

## Requirements and installation

Rialto requires PHP >= 7.2 and Node >= 8.

Install it in your project:

```shell
composer require cnerstudio/rialto
npm install @cnerstudio/rialto
```

## Usage

See our tutorial to [create your first bridge with Rialto](docs/tutorial.md).

An [API documentation](docs/api.md) is also available.

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
