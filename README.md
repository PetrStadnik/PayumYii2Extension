Payum Extension 
================
Upgraded payum extension for Yii2 framework

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

As first paste following code into your composer.json file, which is saved in root folder.

```
"petrstadnik/yii2-payumyii2extension": "*"
```
to the require section of your `composer.json` file.

And add following

```
 "repositories":[
    {
        "type": "git",
        "url": "https://github.com/PetrStadnik/payumyii2extension.git"
    }
]
```
like a new section of your `composer.json` file.


Then via composer run:
```
php composer.phar require --prefer-dist petrstadnik/yii2-payumyii2extension "*"
```




Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \petrstadnik\payumyii2extension\AutoloadExample::widget(); ?>```
