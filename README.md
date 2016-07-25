# PHP-Bitcoin
BitCoin JSON-RPC PHP Helper Class

Composer
---

```
"require": {
  "liamwli/php-bitcoin":"1.0.2"
}
```

Usage
---

```
<?php

use liamwli\PHPBitcoin\BitCoin;

$bitcoin = new BitCoin('rpcuser', 'rpcpassword');
$info = $bitcoin->getinfo(); // Same as $bitcoin->callMethod('getinfo');
```
