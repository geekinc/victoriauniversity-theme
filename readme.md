# Victoria University Theme

[![Build Status](https://travis-ci.org/silverstripe/cwp-starter-theme.svg?branch=master)](https://travis-ci.org/silverstripe/cwp-starter-theme)
[![Packagist](https://img.shields.io/packagist/v/cwp/starter-theme.svg)](https://packagist.org/packages/cwp/starter-theme)
[![SilverStripe supported module](https://img.shields.io/badge/silverstripe-supported-0071C4.svg)](https://www.silverstripe.org/software/addons/silverstripe-commercially-supported-module-list/)

This is the repository for the Victoria University theme. This theme is a highly accessible Bootstrap 4 theme.

![Screenshot](docs/images/screenshot.png)

## Installation

You can install this theme with Composer:

```
{
    "name": "my-agency/my-project",
    "description": "My CWP project",
    "require": {
        "cwp/cwp-recipe-cms": "~2.3.0@stable",
        "geekinc/victoriauniversity-theme": "2.x-dev"
    },
    "require-dev": {
        "cwp/cwp-recipe-basic-dev": "1.0.1"
    },
    "config": {
        "process-timeout": 900
    },
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/geekinc/victoriauniversity-theme.git"
        }
    ],
    "minimum-stability": "dev",
    "prefer-stable": true
}
```

## Documentation

You can find documentation on how to use this theme in the CWP Developer Documentation (where we cloned this repo from): [Customising the starter theme](https://www.cwp.govt.nz/developer-docs/en/2/working_with_projects/customising_the_starter_theme/).

## Requirements

* [Composer](https://getcomposer.org)
* `cwp/cwp`: \^2.0

### Development requirements

* [Node and NPM](https://docs.npmjs.com/getting-started/installing-node)
* [Laravel-Mix](https://github.com/JeffreyWay/laravel-mix) and [Webpack](https://webpack.github.io) (via NPM)

## Versioning

This library follows [Semver](http://semver.org). According to Semver, you will be able to upgrade to any minor or patch version of this library without any breaking changes to the public API. Semver also requires that we clearly define the public API for this library.

All methods, with `public` visibility, are part of the public API. All other methods are not part of the public API. Where possible, we'll try to keep `protected` methods backwards-compatible in minor/patch versions, but if you're overriding methods then please test your work before upgrading.
