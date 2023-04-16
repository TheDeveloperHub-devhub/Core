# Core
​
### Features
* Don’t need to create a menu for every extension. It will automatically attach the menu with your extensions.
* You can simply add the dependency of this core module in your extension.
* This extension is free of cost.
​
## Installation
​
1. Please run the following command
```shell
composer require devhub/core
```
​
2. Update the composer if required
```shell
composer update
```
​
3. Enable module
```shell
php bin/magento module:enable DevHub_Core
php bin/magento setup:upgrade
php bin/magento cache:clean
php bin/magento cache:flush
```
4.If your website is running in product mode the you need to deploy static content and
then clear the cache
```shell
php bin/magento setup:static-content:deploy
php bin/magento setup:di:compile
```
​
​
​
#####This extension is compatible with all the versions of Magento 2.3.* and 2.4.*.
###Tested on following instances:
#####multiple instances i.e. 2.3.7-p3 and 2.4.5-p1
