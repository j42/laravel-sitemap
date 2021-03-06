# [laravel-sitemap](http://roumen.it/projects/laravel-sitemap) package

[![Latest Stable Version](https://poser.pugx.org/j42/laravel-sitemap/version.png)](https://packagist.org/packages/j42/laravel-sitemap) [![Total Downloads](https://poser.pugx.org/j42/laravel-sitemap/d/total.png)](https://packagist.org/packages/j42/laravel-sitemap) [![Build Status](https://travis-ci.org/RoumenDamianoff/laravel-sitemap.png?branch=master)](https://travis-ci.org/RoumenDamianoff/laravel-sitemap) [![License](https://poser.pugx.org/j42/laravel-sitemap/license.png)](https://packagist.org/packages/j42/laravel-sitemap)

A simple sitemap generator for Laravel 4.


## Installation

Add the following to your `composer.json` file :

```json
"j42/laravel-sitemap": "dev-master"
```

Then register this service provider with Laravel :

```php
'Roumen\Sitemap\SitemapServiceProvider',
```

Publish configuration file. (OPTIONAL)

    php artisan config:publish j42/laravel-sitemap


## Examples

[How to generate dynamic sitemap (with optional caching)](https://github.com/RoumenDamianoff/laravel-sitemap/wiki/Dynamic-sitemap)

[How to use multiple sitemaps with sitemap index](https://github.com/RoumenDamianoff/laravel-sitemap/wiki/Sitemap-index)

[How to generate sitemap file](https://github.com/RoumenDamianoff/laravel-sitemap/wiki/Generate-sitemap)

and more in the [Wiki](https://github.com/RoumenDamianoff/laravel-sitemap/wiki)