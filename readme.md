## Code Style

**Editor > Code Style**

Импортировать схему `code-style.xml`.

## Inspections

**Editor > Inspections**

Импортировать профайл `inspections.xml`.

## PHP

**Languages & Frameworks > PHP**

Установить `PHP language level` и `CLI Interpreter` в соответствии с проектом.

## PHP Code Sniffer 

**Languages & Frameworks > PHP > Quality Tools**

В конфигурации Code Sniffer указать путь к `vendor\bin\phpcs.bat`

**Editor > Inspections**

В элементе `PHP > Quality tools > PHP Code Sniffer validation` для поля `Coding standard` указать произвольное значение `vendor/yiisoft/yii2-coding-standards/Yii2/ruleset.xml`.

## Шаблоны файлов

См. **Editor > File and Code Templates**.

Обратите внимание, что в конце PHP-шаблонов пустая строка (в соответствии со стилем кодирования).

### PHP Class

```
<?php

#if (${NAMESPACE})
namespace ${NAMESPACE};
#end

class ${NAME} {

}

```

### Yii2 PHP View File

```
<?php
/**
#foreach( $VAR in $YII2_VIEW_PARAMETERS.split(";") )
 * @var $${VAR}
#end
 */

``` 

## Yii2

**Languages & Frameworks > PHP > Yii2 Support > Views**

В поле `Default View Class` указать класс `View`, используемый в проекте по умолчанию.



