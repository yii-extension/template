<p align="center">
    <a href="https://github.com/yii-extensions/template" target="_blank">
        <img src="https://lh3.googleusercontent.com/9Gh9KzBOJXEmZZBlcASTrmUGNzjfaD6HHt0qtRthAX0a4jBD6-qBrJnglg5bYZGUh5wmR-idUWVHJ3Jh0HKKchnuPfwtD8YV3pHVZaDftfhx0da84gkG2MoPSSSqdVqh5tqTke0Q=w2400" height="50px;">
    </a>
    <h1 align="center">Github Template</h1>
</p>

<p align="center">
    <a href="https://packagist.org/packages/yii-extensions/template" target="_blank">
        <img src="https://poser.pugx.org/yii-extensions/template/v/unstable" alt="Unstable Version">
    </a>
    <a href="https://travis-ci.org/yii-extensions/template" target="_blank">
        <img src="https://travis-ci.org/yii-extensions/template.svg?branch=master" alt="Build Status">
    </a>  
    <a href="https://scrutinizer-ci.com/g/yii-extensions/template/" target="_blank">
        <img src="https://scrutinizer-ci.com/g/yii-extensions/template/badges/build.png?b=master" alt="Build Status">
    </a>
    <a href="https://scrutinizer-ci.com/g/yii-extensions/template/" target="_blank">
        <img src="https://scrutinizer-ci.com/g/yii-extensions/template/badges/coverage.png?b=master" alt="Build Status">
    </a>    
    <a href="https://scrutinizer-ci.com/g/yii-extensions/template/?branch=master" target="_blank">
     	<img src="https://scrutinizer-ci.com/g/yii-extensions/template/badges/quality-score.png?b=master" alt="Code Quality">
    </a>
    <a href="https://scrutinizer-ci.com/code-intelligence" target="_blank">
     	<img src="https://scrutinizer-ci.com/g/yii-extensions/template/badges/code-intelligence.svg?b=master" alt="Code Intelligence Status">
    </a>
    <a href="https://codeclimate.com/github/yii-extensions/template/maintainability" target="_blank">
        <img src="https://api.codeclimate.com/v1/badges/8bfb0df72b3472f6b83d/maintainability" alt="Maintainability">
    </a>		
</p>

</br>

### **REQUIREMENTS:**

- The minimum requirement by this project template that your Web server supports:
    - PHP 7.4 or higher.
    - [Composer Config Plugin](https://github.com/hiqdev/composer-config-plugin)

### **RUN TESTS CODECEPTION:**

~~~
// download all composer dependencies root project
$ composer update --prefer-dist -vvv

// download & run crhomedriver version chrome desktop
$ wget -P vendor/bin https://chromedriver.storage.googleapis.com/75.0.3770.90/chromedriver_linux64.zip
$ unzip -o -q vendor/bin/chromedriver_linux64.zip
$ vendor/bin/chromedriver --port=9515 --url-base=wd/hub/ > /dev/null 2>&1&

// run web server cli php
$ php -S 127.0.0.1:8080 -t tests/public > /dev/null 2>&1&

// run all tests with code coverage
$ vendor/bin/codecept run --coverage-xml
~~~

### **WEB SERVER SUPPORT:**

- Apache.
- Nginx.
- OpenLiteSpeed.

### **DOCUMENTATION STYLE GUIDE:**

[Style CI Documentation PSR2.](https://docs.styleci.io/presets#psr2)

### **LICENCE:**

[![License](https://poser.pugx.org/yii-extensions/template/license)](LICENSE.md)
[![YiiFramework](https://img.shields.io/badge/Powered_by-Yii_Framework-green.svg?style=flat)](https://www.yiiframework.com/)
[![Total Downloads](https://poser.pugx.org/yii-extensions/template/downloads)](https://packagist.org/packages/yii-extensions/template)
[![StyleCI](https://github.styleci.io/repos/202799699/shield?branch=master)](https://github.styleci.io/repos/202799699)
