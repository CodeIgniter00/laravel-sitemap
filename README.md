# **Laravel sitemap package**

[![License](https://poser.pugx.org/laravelium/sitemap/license)](https://packagist.org/packages/laravelium/sitemap)

*Laravel Sitemap generator for Laravel.*

## Notes

- Dev Branches are for development and are **UNSTABLE** (*use on your own risk*)!
- This is a fork of a repository that was deprecated, but I liked it so much that I will continue to maintain it. [Old Repository](https://github.com/Laravelium/laravel-sitemap)

## Installation

Run the following command and provide the latest stable version (e.g v8.\*) :

```bash
composer require laravelium/sitemap
```

*or add the following to your `composer.json` file :*


#### For Laravel 9
```json
"repositories": [
        {
            "type" : "vcs",
            "url" : "https://github.com/codeigniter00/laravel-sitemap"
        }
    ],
```
and
```json
"require" : {
    "codeigniter00/sitemap" : "dev-master"
}
```
#### For Laravel 8
```json
"laravelium/sitemap": "8.*"
```
(development branch)
```json
"laravelium/sitemap": "8.x-dev"
```

#### For Laravel 7
```json
"laravelium/sitemap": "7.*"
```
(development branch)
```json
"laravelium/sitemap": "7.x-dev"
```

#### For Laravel 6
```json
"laravelium/sitemap": "6.*"
```
(development branch)
```json
"laravelium/sitemap": "6.x-dev"
```

#### For Laravel 5.8
```json
"laravelium/sitemap": "3.1.*"
```
(development branch)
```json
"laravelium/sitemap": "3.1.x-dev"
```

#### For Laravel 5.7
```json
"laravelium/sitemap": "3.0.*"
```
(development branch)
```json
"laravelium/sitemap": "3.0.x-dev"
```

#### For Laravel 5.6
```json
"laravelium/sitemap": "2.8.*"
```
(development branch)
```json
"laravelium/sitemap": "2.8.x-dev"
```

#### For Laravel 5.5
```json
"laravelium/sitemap": "2.7.*"
```
(development branch)
```json
"laravelium/sitemap": "2.7.x-dev"
```

*Publish needed assets (styles, views, config files) :*

```bash
php artisan vendor:publish --provider="Laravelium\Sitemap\SitemapServiceProvider"
```
**Note:** *Composer won't update them after `composer update`, you'll need to do it manually!*

## License

This package is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
