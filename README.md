<h1 align="center">
    Logger
</h1>

<p align="center">PHP 日志库</p>  

**安装**  

```shell
composer require duiying/logger
```

**使用**  

```php
// 日志目录：/home/work/logs/common
$logger = \DuiYing\Logger::getInstance();
// 日志目录：/home/work/logs/api
$logger = \DuiYing\Logger::getInstance('api');

$msg = '信息';
$data = ['key' => 'val'];
$logger->info($msg, $data);
```

