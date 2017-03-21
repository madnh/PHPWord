# ![PHPWord](https://rawgit.com/PHPOffice/PHPWord/develop/docs/images/phpword.svg "PHPWord")

Set image:

```php
$templateProcessor->setImg('imageHolder', __DIR__ . DIRECTORY_SEPARATOR . 'resources/image.png');
//or
$templateProcessor->setImg('imageHolder', array('src' => __DIR__ . DIRECTORY_SEPARATOR . 'resources/image.png', 'swh' => '250'));
```

Set text:
```php
$templateProcessor->setValue('serverName', realpath(__DIR__));
$templateProcessor->setText('special_charts', 'http://www.foo.com/index.php?a=1&b=2');
```

Set multiple lines of text
```php
$multi_line_text = implode("\n", ['Text', 'value', 'in', 'multiple', 'of', 'lines']);
$templateProcessor->setText('multi_line_text_1', $multi_line_text);
$templateProcessor->setText('multi_line_text_2', $multi_line_text, true);
```

View `samples/Sample_07_TemplateCloneRow.php` as example.