# PHP GovTalk

**A library for applications which interface with the UK Government Gateway**

[![Build Status](https://travis-ci.org/thebiggive/php-govtalk.png?branch=main)](https://travis-ci.org/thebiggive/php-govtalk)
[![Latest Stable Version](https://poser.pugx.org/thebiggive/php-govtalk/version.png)](https://packagist.org/packages/thebiggive/php-govtalk)
[![Total Downloads](https://poser.pugx.org/thebiggive/php-govtalk/d/total.png)](https://packagist.org/packages/thebiggive/php-govtalk)
[![License](https://poser.pugx.org/thebiggive/php-govtalk/license.svg)](https://packagist.org/packages/thebiggive/php-govtalk)

The GovTalk Message Envelope is a standard developed by the United Kingdom government as a means of encapsulating
a range of government XML services in a single standard data format.

This project was originally forked from [Fubra Limited](https://github.com/fubralimited/php-govtalk). Only the GovTalk
class is preserved in this library. This library can be used whenever you need to build something that interfaces with any
of the services that use the Government Gateway (e.g. Companies House, HMRC, etc.).

## Installation

The library can be installed via [Composer](http://getcomposer.org/). To install, simply add
it to your `composer.json` file:

```json
{
    "require": {
        "thebiggive/php-govtalk": "^1.0"
    }
}
```

And run composer to update your dependencies:

$ curl -s http://getcomposer.org/installer | php
$ php composer.phar update


## Basic usage

This library can be extended and used with any one of the gateways that use the GovTalk Message Envelope and the
Document Submission Protocol. The following libraries currently use / extend GovTalk:

Library | Composer Package | Maintainer
--- | --- | ---
[HMRC Gift Aid](https://github.com/thebiggive/hmrc-gift-aid) | thebiggive/hmrc-gift-aid | [Noel Light-Hilary](https://github.com/noellh)
