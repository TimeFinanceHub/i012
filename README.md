# ss-tfh

librería.

## Installation

The recommended way to install this library is through [Composer](https://getcomposer.org/).

You can create a new project using this library with the following command:

```bash
composer create-project syntaxsanctuary/ss-tfh <my-project>
```

## Packagist Description

The short description of the project that appears on Packagist before the README is configured in the `description` field of your `composer.json` file.

```json
{
    "name": "syntaxsanctuary/ss-tfh",
    "description": "librería.",
    "type": "library",
    "license": "MIT",
    "authors": [
        {
            "name": "Ramiro",
            "email": "mostlyphpsoftware@email.com"
        }
    ],
    "minimum-stability": "stable",
    "require": {
        "php": "^8.1"
    },
    "autoload": {
        "psr-4": {
            "syntaxsanctuary\\ss-tfh\\": "src/"
        }
    }
}
```

