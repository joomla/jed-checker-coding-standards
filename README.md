# jed-checker-coding-standards
JED Checker Coding Standards

This repository migrated the Jed checker rules to PHPCS3.x.

## Requirements

* PHP 5.6+
* [PHP Codesniffer](https://github.com/squizlabs/PHP_CodeSniffer) 3.3.0+
* [Joolma coding standards](https://github.com/joomla/coding-standards/tree/3.x-dev)
* Once installed (or copied), copy the "Joomla" folder into /root/.config/composer/vendor/joomla/coding-standards/Joomla. This will add our rules and sniffs. We must also overwrite the file located into /root/.config/composer/vendor/squizlabs/php_codesniffer/src/Reporter.php with the Reporter.php included here.

## Running

You can use the installed jed standard like:

	phpcs --standard=jed path/to/code

Alternatively if it isn't installed you can still reference it by path like:

	phpcs --standard=path/to/jed/ExampleRulesets/Joomla-JEDChecker.xml path/to/code

