# SEO-METATAG
Метатеги из файла 
```php
<? $APPLICATION->ShowHeadScripts();?>
<? $APPLICATION->ShowHeadStrings();?>
<? $APPLICATION->ShowCSS() ?>
<? 
	$seo = $_SERVER["DOCUMENT_ROOT"] . "/include/seo.lib.php"; 
	if (file_exists($seo)) include ($seo); 
?>
```
