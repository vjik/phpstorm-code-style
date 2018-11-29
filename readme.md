## Code Style

**Editor > Code Style**

Импортировать схему `code-style.xml`.

## Inspections

**Editor > Inspections**

Импортировать профайл `inspections.xml`.

## PHP

**Languages & Frameworks > PHP**

Установить `PHP language level` и `CLI Interpreter`.

## PHP Code Sniffer 

**Languages & Frameworks > PHP > Quality Tools**

В конфигурации Code Sniffer указать путь к `vendor\bin\phpcs.bat`

**Editor > Inspections**

В элементе `PHP > Quality tools > PHP Code Sniffer validation` для поля `Coding standard` указать произвольное значение `vendor/yiisoft/yii2-coding-standards/Yii2/ruleset.xml`.

## Шаблоны файлов

### PHP Class

```
<?php

#if (${NAMESPACE})
namespace ${NAMESPACE};
#end

class ${NAME} {

}

```

Обратите внимание, что в конце шаблона пустая строка (в соответствии со стилем кодирования).