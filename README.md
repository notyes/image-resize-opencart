# Exp,, for resize image ( opencart )


```php
include_once 'image.php';
$m = new Image('./1.png');
$m->resize(500,800);
$m->save('./2.png');
header('Content-Type: image/png');
readfile('2.png');

```