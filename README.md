[![Latest Stable Version](https://poser.pugx.org/wend/phpqatools/v/stable.png)](https://packagist.org/packages/wend/phpqatools) [![Build Status](https://travis-ci.org/wendtecnologia/phpqatools.svg?branch=master)](https://travis-ci.org/wendtecnologia/phpqatools) [![License](https://poser.pugx.org/wend/phpqatools/license.png)](https://packagist.org/packages/wend/phpqatools) 
PHP QA Tools 
============

A meta package for composer of PHP QA Tools, to simplify the installation and configuration of necessary packages:

- PHPUnit
- PHPCodeSniffer
- PHPLOC
- PDepend
- PHPMD
- PHPCPD
- PHPDocumentor

PS.: We included latest versions of each item from http://jenkins-php.org/installation.html:

# Installation

## Installing Composer at global context

    $ curl -sS https://getcomposer.org/installer | php
    $ mv composer.phar /usr/local/bin/composer

## Installing all tools

For a system-wide installation via composer, you can run:

    $ composer global require 'wend/phpqatools=*'

Make sure you have `~/.composer/vendor/bin/` in your path.

Testing if its ok:

    $ phploc --version

# Versioning

Its based on http://semver.org/

