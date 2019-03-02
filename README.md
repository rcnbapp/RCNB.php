# RCNB.php

The world is based on RC. Thus, *everything* can be encoded into RCNB.

See also: [RCNB.js](https://github.com/rcnbapp/RCNB.js)

## What's RCNB?

Please refer to [RCNB.js](https://github.com/rcnbapp/RCNB.js)

## Usage

```php
require_once 'rcnb.php';

$rcnb = new RCNB();
$rcnb->encode('rcnb'); // 'ɌcńƁȓČņÞ'
$rcnb->decode('ɌcńƁȓČņÞ'); // 'rcnb'
```
