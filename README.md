HttpLib - Library contain http codes and methods
========================

Used to contain all required data in one place

Usage
-----

Simple example

```php
<?php

use HttpLib\Http;

$this->sendRequest(Http::METHOD_GET, 'http://google.com/');

$this->response(Http::CODE_OK, ['result' => ['any data']]);
```