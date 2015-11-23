# Soap Handler for Whoops

Captures exceptions and returns information on them as a SOAP string. Might be used for SOAP Webservices.

```php
require 'vendor/autoload.php';

$handler = new \Whoops\Handler\SoapResponseHandler();
$run->addHandler($handler);
```
