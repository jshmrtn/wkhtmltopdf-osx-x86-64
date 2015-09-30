wkhtmltopdf
================

This repository contains the OS X (>=10.6) binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use '0.12.2.1'.

In case this package does _not_ work on your system, try installing the matching system packages from here: [http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html).

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

    php composer.phar require jshmrtn/wkhtmltopdf-osx-x86-64 "0.12.2.1"

The binaries will then be located at:

    vendor/jshmrtn/wkhtmltopdf-osx-x86-64/bin/wkhtmltopdf-osx-x86-64
    vendor/jshmrtn/wkhtmltopdf-osx-x86-64/bin/wkhtmltoimage-osx-x86-64

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltopdf-osx-x86-64
    vendor/bin/wkhtmltoimage-osx-x86-64

