# ![PHPWord](https://rawgit.com/PHPOffice/PHPWord/develop/docs/images/phpword.svg "PHPWord")

Set image:

```php
$templateProcessor->setImg('imageHolder', __DIR__ . DIRECTORY_SEPARATOR . 'resources/image.png');
//or
$templateProcessor->setImg('imageHolder', array('src' => __DIR__ . DIRECTORY_SEPARATOR . 'resources/image.png', 'swh' => '250'));
```

View `samples/Sample_07_TemplateCloneRow.php` as example.