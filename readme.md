#SamsonPHP

[SamsonPHP](http://samsonphp.com) - Modular Event-based PHP framework

##Using SamsonPHP in your project
To use SamsonPHP framework in your project you must add its dependency in your ```composer.json```:
```
    "minimum-stability":"dev",
    "require": {
        "samsonos/php_core": "*"
    },
```
After doing ```composer install``` or ```composer update``` composer autoloader must be included
into your init script(by default ```index.php```): ```require [PATH_TO_VENDOR_DIR]/autoload.php```.
Following this line, all SamsonPHP classes and functions would be available.

> We should use ```"minimum-stability":"dev"``` composer directive as we still cannot get
> final release version of core module and other commonly used modules, but we promise to
> do it near future

##Loading modules into SamsonPHP framework
All modules are loaded via composer.json file section ```require:...``` and follows all PSR-0 rules.

Developed by [SamsonOS](http://samsonos.com/)