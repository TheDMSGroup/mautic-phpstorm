# Code Styles for Mautic + PHP-CS + PHPStorm

A coding style format for PHPStorm (Intellij) that:
- Fits Symfony2 standards
- Closely matches the PHP-CS requirements for Mautic (though not perfectly)
- Follows implied styles that the Mautic community at large is following

## Known Issues
- Aligning PHPDoc variable comments is only accepted if all variables have comments, because PHPstorm indents minimally where PHP-CS indents to the maximum variable name regardless of comments.
- Some equal sign indentations are ignored, because PHPStorm is aligning based on types, where PHP-CS indents all lines containing equal signs.
- [Yoda](https://en.wikipedia.org/wiki/Yoda_conditions) conditions are not supported.

So this doesn't mean you don't ever have to use PHP-CS if you are making PRs to core,
but at least the code style of PHPStorm will not compete with PHP-CS so that you can get the best of both worlds. :)

## Installation

- Download the [Mautic.xml](https://rawgit.com/TheDMSGroup/mautic-php-cs-phpstorm/master/Mautic.xml) file.
- Install the Code Style under Preferences > Editor > Code Style > PHP > Scheme > Import Scheme > Intellij IDEA code style XML

![](screenshot.png?raw=true)
