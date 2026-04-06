## Clone of PHP Chess

A chess library offering move validation, common formats, multiple variants, UCI engine support, explanation of chess positions, image recognition, PGN parsing and knowledge extraction from games.

## Installation

This package can be installed via [Composer](https://getcomposer.org/). Since it is hosted directly on GitHub, you need to add the repository to your `composer.json` file.

### 1. Configure `composer.json`

Add the following sections to your project's `composer.json`:

```json
{
    "repositories": [
        {
            "type": "vcs",
            "url": "[https://github.com/2700chess/php-chess](https://github.com/2700chess/php-chess)"
        }
    ],
    "require": {
        "2700chess/php-chess": "*"
    }
}
```

### 2. Run Installation

```
composer update 2700chess/php-chess
```

### License

PHP Chess is open-sourced software licensed under the MIT license.
