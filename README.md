ImageBehavior for Yii2
======================
Small extension which adds useful ImageBehavior to easily maintain images linked to the Model and easily create their thumbnails on the fly

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist noneedinmagic/yii2-image-behavior "*"
```

or add

```
"noneedinmagic/yii2-image-behavior": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \noneedinmagic\images\AutoloadExample::widget(); ?>```