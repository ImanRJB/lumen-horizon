## Installation

The installation is almost the same as original package.

Note that the package namespace remains `Laravel\Horizon`, so don't install it along with original one to avoid conflicts.

1. Composer dependency manager:

```bash
    composer require imanrjb/lumen-horizon
```

2. Publish `horizon.php` file to the config folder:

```bash
    php artisan vendor:publish --tag=horizon-config
```

or, as suggested in the official package docs:

```bash
    php artisan vendor:publish --provider="Laravel\Horizon\HorizonServiceProvider"
```


## Official Documentation

Documentation for Horizon can be found on the [Laravel website](http://laravel.com/docs/master/horizon).