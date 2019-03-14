# RCNB.php

The world is based on RC. Thus, *everything* can be encoded into RCNB.

RCNB is available in various languages: [JavaScript](https://github.com/rcnbapp/RCNB.js) [C](https://github.com/rcnbapp/librcnb) **PHP** [Pascal](https://github.com/rcnbapp/RCNB.pas) ([more..](https://github.com/rcnbapp/))

## What's RCNB?

Please refer to [RCNB.js](https://github.com/rcnbapp/RCNB.js)

## Usage

```php
require_once 'rcnb.php';

$rcnb = new RCNB();
$rcnb->encode('rcnb'); // 'ɌcńƁȓČņÞ'
$rcnb->decode('ɌcńƁȓČņÞ'); // 'rcnb'
```
