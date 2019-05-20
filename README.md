# PHP CS Fixer preset

This is for internal use, but feel free to use it.

## Requirements

1. PHP (for sure).
2. PHP CS FIXER installed locally or globally
3. Composer


## Usage

In your composer script section you can add the following:

```json
    "format" : [
        "@php ./vendor/bin/php-cs-fixer fix --config=php_cs.php.dist --using-cache=no"
    ],
```

This assume that you are using php-cs-fixer locally and not installed globally.

## Info

This preset use PSR2 rule set and the set which was defined for Laravel at https://styleci.io.

