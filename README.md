# PHP Clipboard

This is a 5-minute package I threw togehter that simply wraps the Mac, Windows, and (most common) Linux commands for copying contents to the clipboard. I don't handle reading files. You'll have to do that yourself. I simply pipe whatever contents you provide to the appropriate command based on the operating system reported by php_uname().
Originally created by Ed Grosvenor (https://github.com/edgrosvenor/php-clipboard). Dependencies updated (PHP >=7.2).

### Installation
```shell script
composer require klkmva/php-clipboard
```

### Usage
```php
<?php

use klkmva\PHPClipboard\Clipboard;

Clipboard.copy('string');
```
