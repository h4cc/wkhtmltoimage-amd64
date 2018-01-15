wkhtmltoimage
================

This repository contains the static compiled binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use '0.12.4'.

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package for _i386_ with:

    php composer.phar require h4cc/wkhtmltoimage-i386 "0.12.4"

And for _amd64_ with:

    php composer.phar require h4cc/wkhtmltoimage-amd64 "0.12.4"

The binary will then be located at:

    vendor/h4cc/wkhtmltoimage-i386/bin/wkhtmltoimage-i386

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltoimage-i386
