# jed-checker-coding-standards
JED Checker Coding Standards

This repository migrated the Jed checker rules to PHPCS3.x.

## Requirements

* PHP 5.6+
* [PHP Codesniffer](https://github.com/squizlabs/PHP_CodeSniffer) 3.3.0+
* Once installed (or copied), we must overwrite the file located into /root/.config/composer/vendor/squizlabs/php_codesniffer/src/Reporter.php with the Reported.php included here.

## Installation via Composer

## Running

You can use the installed jed standard like:

	phpcs --standard=jed path/to/code

Alternatively if it isn't installed you can still reference it by path like:

	phpcs --standard=path/to/jed/ExampleRulesets/Joomla-JEDChecker.xml path/to/code

