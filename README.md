MultiSelect Widget for Yii2
==============================

Renders a [MultiSelect Bootstrap plugin](http://davidstutz.github.io/bootstrap-multiselect) widget.

Installation
------------
The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require 2amigos/yii2-multi-select-widget "*"
```
or add

```json
"2amigos/yii2-multi-select-widget" : "*"
```

to the require section of your application's `composer.json` file.

Usage
-----
Using a model:

```
use dosamigos\multiselect\MultiSelect;

<?= MultiSelect::widget([
    'data' => [0 => 'super', 1 => 'natural'],
    'value' => [ '0' ]
    'name' => 'Test',
    'options' => [
        'multiple' => 'multiple'
    ]
]) ?>
```
