# BEM-HELP

Инструмент для работы с файловой системой по БЕМ методологии. Предоставляет команды для создания или переименования БЕМ сущностей.

## Использование

По умолчанию команды создают папки с соответствующими названиями. Можно передать дополнительные параметры `--bemhtml`, `--css`, `--js` &mdash; в результате будут созданные соответствующие файлы.

Создание блока:
```
mkbem <block-name>
```

Создание модификатора блока:
```
mkbem -c <block-name>_<mod-name>_<mod-value>
```

Создание элемента блока:
```
mkbem <block-name>__<elem-name>
```
