# Config PhpStorm

## External Tools

### php-cs-fixer (file, symfony)

- Description : ``fix php-cs in current file``
- Program : ``php``
- Parameters : ``C:\EasyPHP\data\localweb\php-cs-fixer.phar --level=symfony fix $FileDir$/$FileName$``
- Working directory : ``$ProjectFileDir$``

### php-cs-fixer (project, symfony)

- Description : ``fix php-cs in current project``
- Program : ``php``
- Parameters : ``C:\EasyPHP\data\localweb\php-cs-fixer.phar --config=sf23 -vvv fix $ProjectFileDir$``
- Working directory : ``$ProjectFileDir$``
