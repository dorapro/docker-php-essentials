dorapro/php-essentials
======================

## Includes
- PHP Coding Standards Fixer (php-cs-fixer)
    - http://cs.sensiolabs.org/
    - https://github.com/FriendsOfPHP/PHP-CS-Fixer
- PHP_CodeSniffer (phpcs, phpcbf)
    - https://github.com/squizlabs/PHP_CodeSniffer
- PHP Mess Detector (phpmd)
    - https://phpmd.org/
    - https://github.com/phpmd/phpmd
- PhpMetrics (phpmetrics)
    - http://www.phpmetrics.org/
    - https://github.com/phpmetrics/PhpMetrics
- PHPLOC (phploc)
    - https://github.com/sebastianbergmann/phploc

## Usages
working directory: `/app`

```sh
docker run --rm -v $(pwd):/app dorapro/php-essentials COMMAND

# COMMAND
# - php-cs-fixer
# - phpcs
# - phpcbf
# - phpmd
# - phpmetrics
# - phploc
```
