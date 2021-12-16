# PHP-I18N
#### A PHP library for internationalization

---
### Installation
```shell
composer require php-i18n
```
or add the following to your `composer.json`:
```json
{
  "require": {
    "php-i18n/php-i18n": "v1.0"
  }
}
```

---

### Usage
```php
<?php

require 'vendor/autoload.php';

$i18n = new \MrMuminov\PhpI18n\I18n([
    'languages' => ['en', 'uz'],
    'language' => 'en',
]);

echo $i18n->get('Home');
// Output: "Home"

echo $i18n->get('Hello %s', 'John');
// Output: "Hello John"
```


---

### Author
- [Bahriddin Mo'minov](https://github.com/mrmuminov)
