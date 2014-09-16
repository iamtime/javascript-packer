PHP 5 :
use class.JavaScriptPacker.php (Tested under PHP 5.1.2, 5.1.3, 5.1.4, 5.2.3.)
 - usage and comments in source.
 - there is 2 examples in this archive for PHP 5,
   'example-file.php' and example-inline.php

PHP 4 :
use class.JavaScriptPacker.php4, it's an adaptation for PHP4.
The examples in this archive will not work directly with PHP 4, they are
writed in PHP5, you'll need to adapt them. If some functions are missing in
PHP 4, you can find their equivalent here :
http://pear.php.net/package/PHP_Compat


@edited by ptcong90 <ptcong90 at gmail dot com>
@date Aug 13, 2014
@changes
- Fixed wrong revert string '\n' (previous time the class revert '\n' to '\')
- Improved rename variables to special character (any -> a, any -> b, and ->c) instead of (pack -> p, packer -> p ??)
