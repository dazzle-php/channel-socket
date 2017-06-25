# Dazzle Async Socket Channel

[![Build Status](https://travis-ci.org/dazzle-php/channel-socket.svg)](https://travis-ci.org/dazzle-php/channel-socket)
[![Code Coverage](https://scrutinizer-ci.com/g/dazzle-php/channel-socket/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/dazzle-php/channel-socket/?branch=master)
[![Code Quality](https://scrutinizer-ci.com/g/dazzle-php/channel-socket/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/dazzle-php/channel-socket/?branch=master)
[![Latest Stable Version](https://poser.pugx.org/dazzle-php/channel-socket/v/stable)](https://packagist.org/packages/dazzle-php/channel-socket) 
[![Latest Unstable Version](https://poser.pugx.org/dazzle-php/channel-socket/v/unstable)](https://packagist.org/packages/dazzle-php/channel-socket) 
[![License](https://poser.pugx.org/dazzle-php/channel-socket/license)](https://packagist.org/packages/dazzle-php/channel-socket/license)

<br>
<p align="center">
<img src="https://avatars0.githubusercontent.com/u/29509136?v=3&s=150" />
</p>

## Description

Dazzle Channel-Socket is a component that uses asynchronous sockets to implement transport model for Dazzle Channel.

## Feature Highlights

Dazzle Channel-Socket features:

* Channel model implementation using sockets,
* Heartbeat mechanism,
* Reconnect mechanism,
* Event-based & Promise-based API,
* ...and more.

## Requirements

* PHP-5.6 or PHP-7.0+,
* UNIX or Windows OS.

## Installation

```
$> composer require dazzle-php/channel-socket
```

## Tests

```
$> vendor/bin/phpunit -d memory_limit=1024M
```

## Contributing

Thank you for considering contributing to this repository! The contribution guide can be found in the [contribution tips][1].

## License

Dazzle Framework is open-sourced software licensed under the [MIT license][2].

[1]: https://github.com/dazzle-php/channel-socket/blob/master/CONTRIBUTING.md
[2]: http://opensource.org/licenses/MIT
