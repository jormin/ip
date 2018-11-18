# 说明

解析IP地址，使用 [ipip.net](http://www.ipip.net/) 的服务。

## 安装

 1. 安装包文件

	``` bash
	$ composer require jormin/ip
	```

## 使用

1. 代码中使用
    
   获取地址数组
    
    ```php
    Jormin\IP\IP:ip2addr('your ip');
    ```
    
    获取地址字符串
    ```php
    Jormin\IP\IP:ip2addr('your ip', 'your glue');
    ```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
