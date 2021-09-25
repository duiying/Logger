<h1 align="center">
    logger
</h1>

<p align="center">PHP 日志库</p>  

**安装**  

```shell
composer require duiying/logger
```

**使用**  

```php
// 默认日志目录：/home/work/logs/common
$logger = \DuiYing\Logger::getInstance();
// 自定义日志目录
$logger = \DuiYing\Logger::getInstance('/home/work/logs/api');

$msg = '信息';
$data = ['key' => 'val'];
$logger->info($msg, $data);
```

