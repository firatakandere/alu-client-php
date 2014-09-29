# PayU Automatic Live Update Client Library - V1.0

## Prerequisites

 * PHP 5.3 and above
 * curl extension with support for OpenSSL
 * PHPUnit 4.2.0 for running test suite (Optional)
 * Composer (Optional)

## Composer

You can install the library via [Composer](http://getcomposer.org/). Add this to your composer.json:

    {
      "require": {
        "payu/alu-client": "1.*"
      }
    }

Then install via:

    composer install

To use the library, include Composer's [autoload](https://getcomposer.org/doc/00-intro.md#autoloading]):

    require_once('vendor/autoload.php');

## Manual Installation

Obtain the latest version of the PayU Automatic Live Update Client Library with:

    git clone https://github.com/payu/alu-client

To use the Library, add the following to your PHP script:

    require_once("/path/to/payu/alu-client/src/init.php");

## Getting Started

You can find usage examples in the examples directory:

* basicExample.php - Minimal requirements for order authorization via ALU protocol using Credit Card Information (If you are PCI DSS compliant)
* tokenPayment.php - Minimal requirements for order authorization via ALU protocol using Token
* threeDSReturn.php - Example of return from 3D Secure authorization and response