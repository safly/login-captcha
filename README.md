laravel-admin login-captch
======

Installation
First, install dependencies:

    composer require james.xue/login-captcha
 
Configuration
 In the extensions section of the config/admin.php file, add some configuration that belongs to this extension.
 
     'extensions' => [
         'login-captcha' => [
             // set to false if you want to disable this extension
             'enable' => true,
         ]
     ]
 
 
