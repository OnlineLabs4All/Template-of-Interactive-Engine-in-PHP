Template of Interactive Engine in PHP
=====================================

This template of an Interactive Engine checks if the coupon issued by the iLab Service Broker is valid and loads the lab client in that case.

## How to start?
Change $authUser, $authPass and $X_apikey in index.php. You get them from the Dispatcher (http://dispatcher.onlinelabs4all.org/) by creating a new Experiment Engine. At the bottom of index.php replace the line
```php
echo '<b>Success!</b> Load Client...';
```
with your Interactive Lab Client by using PHP's include-function. To keep the folder structure clean use the folder "client". Note that the include-function of PHP can also have an influence on relative paths of the loaded document.
