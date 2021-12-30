# mysqldb


## install via composer
```composer
composer require elshawadfi/mysqldb
```

## use

```php
require "vendor/autoload.php";


 use Elshawadfi\Mysqldb\MysqlDB;

$db = new MysqlDB("localhost", "root", "password", "test");


```