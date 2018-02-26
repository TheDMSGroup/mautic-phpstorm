# mautic-cs-phpstorm

A coding style format that:
- Fits Symfony2 standards
- Closely matches the PHP-CS requirements for Mautic (not perfectly)
- Follows implied styles that the Mautic community at large is following

## Known Issues
- Aligning PHPDoc variable comments is only accepted if all variables have comments, because PHPstorm indents minimally where PHP-CS indents to the maximum variable name regardless of comments.
- Some equal sign indentations are ignored, because PHPStorm is aligning based on types, where PHP-CS indents all lines containing equal signs.
- [Yoda](https://en.wikipedia.org/wiki/Yoda_conditions) conditions are not supported.

So this doesn't mean you don't have to use PHP-CS, but at least the code style of PHPStorm will not compete with PHP-CS :)
