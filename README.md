# Soap Handler for Whoops

[![Build Status](https://travis-ci.org/whoops-php/soap.svg)](https://travis-ci.org/whoops-php/soap)

Captures exceptions and returns information on them as a SOAP string. Might be used for SOAP Webservices.

```php
require 'vendor/autoload.php';

$handler = new \Whoops\Handler\SoapResponseHandler();
$run->addHandler($handler);
```
