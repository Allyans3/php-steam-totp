# php-steam-totp

This forks removes deprecated warnings on PHP 8

```composer require allyans3/php-steam-totp```

https://packagist.org/packages/allyans3/php-steam-totp

PHP library for TOTP for use with [Steam](http://steampowered.com). It's documented with phpdoc; just read it to learn
how to use it.

Only requirement is cURL.

# Example

```php
<?php
require_once 'vendor/autoload.php'; // if you're using composer

use SteamTotp\SteamTotp;

echo "Login code: " . SteamTotp::getAuthCode("cnOgv/KdpLoP6Nbh0GMkXkPXALQ=");
```
