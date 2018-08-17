# Learning Laravel 

## Installation

- Download and install [**XAMPP**](https://www.apachefriends.org/download.html)
- Enable the following extensions on **XAMPP** `php.ini`, normally you can find this inside the folder `C:\PATH_TO_xampp\php` 
```
extension=php_openssl.dll
extension=php_curl.dll
```

- Download and install [**PHP Composer**](https://getcomposer.org/download/)
- Open the command prompt by pressing the `windows-key + R`
```
cd C:\PATH_TO_xampp\htdocs
composer create-project laravel/laravel quickstart --prefer-dist
```
- You can now access the Laravel quickstart on http://localhost/laravel/public/

