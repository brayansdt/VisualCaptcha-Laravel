VisualCaptcha-Laravel
=======================

VisualCatpcha library adapted for Laravel

This package is available on Packagist:
https://packagist.org/packages/metrakit/visualcaptcha-laravel

And on Packalyst:
http://packalyst.com/packages/package/metrakit/visualcaptcha-laravel

##How to install

- Add the package to your composer.json:

    ```json
"metrakit/visualcaptcha-laravel": "~v1.0"
    ```
    
- Use the command : 
```
composer update
```
- Add these lines top the "app.php" file in the config folder where is the "aliases" category :

    ```php 
// VisualCaptcha - Captcha library
'Captcha'          => 'visualCaptcha\Captcha',
'SessionCaptcha'   => 'visualCaptcha\SessionCaptcha',
    ```
    
It's all !

##DEMO
You have an example here: https://github.com/Metrakit/VisualCaptcha-Laravel/tree/master/example

##OFFICIAL WEBSITE
This library is from VisualCaptcha of EmotionLoop : http://visualcaptcha.net.

I have only adapted it for Laravel 4
