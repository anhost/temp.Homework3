# Mystery Sequence Library

Библиотека `Mystery Sequence` предоставляет простую, но загадочную последовательность чисел, которая известна тем, что вызывает любопытство и интерес у тех, кто её обнаруживает.

## Установка

Вы можете установить библиотеку через [Composer](https://getcomposer.org/). Запустите следующую команду:

```bash
composer require dshevchenko/mysterysequence
```

## Использование

Использовать библиотеку `Mystery Sequence` очень просто. После установки вы можете получить последовательность следующим образом:

```php
<?php

require_once 'vendor/autoload.php';

use Dshevchenko\Mysterysequence\Sequence;

$sequence = new Sequence();
print_r($sequence->get());
```

Это выведет:

```
Array
(
    [0] => 4
    [1] => 8
    [2] => 15
    [3] => 16
    [4] => 23
    [5] => 42
)
```

## Требования

- PHP 7.4 or higher