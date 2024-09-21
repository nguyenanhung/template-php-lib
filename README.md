[![Latest Stable Version](https://img.shields.io/packagist/v/nguyenanhung/template-php-lib.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/template-php-lib)
[![Total Downloads](https://img.shields.io/packagist/dt/nguyenanhung/template-php-lib.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/template-php-lib)
[![Daily Downloads](https://img.shields.io/packagist/dd/nguyenanhung/template-php-lib.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/template-php-lib)
[![Monthly Downloads](https://img.shields.io/packagist/dm/nguyenanhung/template-php-lib.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/template-php-lib)
[![License](https://img.shields.io/packagist/l/nguyenanhung/template-php-lib.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/template-php-lib)
[![PHP Version Require](https://img.shields.io/packagist/dependency-v/nguyenanhung/template-php-lib/php)](https://packagist.org/packages/nguyenanhung/template-php-lib)

# Template start helper, library

Template for repository helper, library - Basic, Simple and Lightweight

## Use this Template

First, you can `Use this template` for new project: [Use this template](https://github.com/nguyenanhung/template-php-lib/generate)

Second, clone your project to your to path in your machine

Finally, your edit file `composer.json` in root folder of project

```json
{
    "type": "library",
    "name": "nguyenanhung/template-php-lib",
    "description": "Template for repository helper, library - Basic, Simple and Lightweight",
    "keywords": [
        "template",
        "helper",
        "library",
        "php"
    ],
    "homepage": "https://github.com/nguyenanhung/template-php-lib",
    "license": "MIT",
    "minimum-stability": "stable",
    "authors": [
        {
            "name": "Nguyen An Hung",
            "email": "dev@nguyenanhung.com",
            "homepage": "https://nguyenanhung.com",
            "role": "Developer"
        }
    ],
    "require": {
        "php": ">=5.6"
    },
    "autoload": {
        "psr-4": {
            "nguyenanhung\\Libraries\\REPLACE_FOR_YOUR\\": "src/"
        },
        "files": [
            "helpers/helpers.php"
        ]
    }
}

```

Replace name space `REPLACE_FOR_YOUR` to Library space, example: `JSON`. After change namespace, project namespace same `"nguyenanhung\\Libraries\\JSON\\": "src/"`

Finished, your can writing new awesome helper and library now time.

## Contact & Support

If any question & request, please contact following information

| Name        | Email                | Skype            | Facebook      |
|-------------|----------------------|------------------|---------------|
| Hung Nguyen | dev@nguyenanhung.com | nguyenanhung5891 | @nguyenanhung |

From Vietnam with Love <3
