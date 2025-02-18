---
description: djLint Изменения. Ознакомьтесь с обновлениями последних релизов и узнайте, какие функции вы можете ожидать при следующем обновлении.
title: Изменения
keywords: облицовка шаблонов, форматер шаблонов, djLint, HTML, шаблоны, форматер, линтер, использование, Изменения
---

{% raw %}

# Изменения

<!--## {{ "next_release" i18n }}-->
## 1.0.0
::: content
- Исправления ошибок [#224](https://github.com/Riverside-Healthcare/djLint/issues/224)
  :::

## 0.7.6

::: content
- Исправления ошибок [#189](https://github.com/Riverside-Healthcare/djLint/issues/189), [#197](https://github.com/Riverside-Healthcare/djLint/issues/189)
- Добавлен флаг `--warn` для возврата ошибок в виде предупреждений.
  :::

## 0.7.5

::: content

- Исправления ошибок [#187](https://github.com/Riverside-Healthcare/djLint/issues/187)
- Добавлена улучшенная поддержка ``yaml`` front matter в файлах шаблонов
- Добавлено правило T032 для [#123](https://github.com/Riverside-Healthcare/djLint/issues/123)
- Добавлено правило H033 для [#124](https://github.com/Riverside-Healthcare/djLint/issues/124)
- Изменены профили линтеров, чтобы они были инклюзивными, а не эксклюзивными для [#178](https://github.com/Riverside-Healthcare/djLint/issues/178)
- Добавлена альтернативная опция файла конфигурации ``.djlintrc`` для [#188](https://github.com/Riverside-Healthcare/djLint/issues/188)
  :::

## 0.7.4

::: content

- Исправления ошибок [#177](https://github.com/Riverside-Healthcare/djLint/issues/177)
  :::

## 0.7.3

::: content

- Исправления ошибок [#173](https://github.com/Riverside-Healthcare/djLint/issues/173), [#174](https://github.com/Riverside-Healthcare/djLint/issues/174)
- Упал Py3.6 с сайта `pyproject.toml`.
  :::

## 0.7.2

::: content

- Исправления ошибок [#167](https://github.com/Riverside-Healthcare/djLint/issues/167), [#166](https://github.com/Riverside-Healthcare/djLint/issues/166), [#171](https://github.com/Riverside-Healthcare/djLint/issues/171), [#169](https://github.com/Riverside-Healthcare/djLint/issues/169)
  :::

## 0.7.1

::: content

- Исправления ошибок [#166](https://github.com/Riverside-Healthcare/djLint/issues/166)
  :::

## 0.7.0

::: content

- Добавлена настройка для пользовательских HTML-тегов
- Исправления ошибок
  :::

## 0.6.9

::: content

- Добавлены профили HTML и Angular
- Разрешены некоторые сущности в правиле #H023
- Исправления ошибок
  :::

## 0.6.8

::: content

- Исправления ошибок
- Обновленные документы
  :::

## 0.6.7

::: content

- Добавлена опция конфигурации `format_attribute_template_tags` как опция для форматирования тегов шаблонов внутри атрибутов
- Добавлена опция конфигурации `linter_output_format` для настройки порядка переменных сообщений линтера
- Добавлены правила H030 и H031 для проверки мета-тегов
  :::

## 0.6.6

::: content

- Большие исправления
  :::

## 0.6.5

::: content

- Обновлены пути вывода, чтобы они были относительными к корню проекта
- Исправления ошибок
  :::

## 0.6.4

::: content

- Исправления ошибок
  :::

## 0.6.3

::: content

- Добавлена поддержка тега django `blocktrans`.
- Исправления ошибок
  :::

## 0.6.2

::: content

- Исправления ошибок
  :::

## 0.6.1

::: content

- Исправления ошибок
- Сделать правило T028 более строгим с более четким посланием
  :::

## 0.6.0

::: content

- Добавлено правило T027 для проверки наличия незакрытых тегов в синтаксисе шаблона
- Добавлено правило T028 для проверки отсутствия пробельных тегов в атрибутах
- Добавлено правило H029 для проверки метода формы в нижнем регистре
- Игнорируются теги djagno blocktranslate, которые не имеют "trimmed" от форматера
- Исправления ошибок
  :::

## 0.5.9a

::: content

- Добавлена поддержка тестирования для python 3.10
- Добавлен крючок предварительного коммита
  :::

## 0.5.9

::: content

- Добавлена опция `--use-gitignore` для расширения исключений
- Изменено сопоставление исключений по умолчанию
- Исправлены пути исключения окон
- Исправлено форматирование тегов `{%...%}` в атрибутах
- Исправлено форматирование циклов for и вложенных условий в атрибутах
  :::

## 0.5.8

::: content

- Добавлена опция require_pragma
- Обновлен DJ018 для перехвата `data-src` и `action` на входах
- Исправлен синтаксис игнорирования строк
- Добавлена опция `--lint` в качестве заполнителя для использования по умолчанию
- Исправления ошибок
  :::

## 0.5.7

::: content

- Исправления ошибок
  :::

## 0.5.6

::: content

- Добавлено правило H026 для поиска пустых тегов id и class
- Исправления ошибок
  :::

## 0.5.5

::: content

- Консолидированные настройки и сокращенный код
- Исправления ошибок
  :::

## 0.5.4

::: content

- Добавлено правило H020 для поиска пустых пар тегов
- Добавлено правило H021 для поиска инлайн-стилей
- Добавлено правило H022 для поиска http-ссылок
- Добавлено правило H023 для поиска ссылок на сущности
- Добавлено правило H024 для поиска типов в скриптах и стилях
- Добавлено правило H025 для проверки сиротских тегов. Благодаря https://stackoverflow.com/a/1736801/10265880
- Улучшено форматирование атрибутов
- Обновлена опция `blank_line_after_tag` для добавления новой строки независимо от местоположения
- Исправлено форматирование тегов django `trans`
- Добавлено форматирование для встроенных стилей
- Добавлено форматирование для условий шаблона внутри атрибутов
- Добавлен srcset как возможное местоположение url в правилах линтера
- Ускорено форматирование
- Особая благодарность [jayvdb](https://github.com/jayvdb>)
  :::

## 0.5.3

::: content

- Измените stdout для опций `--reformat/check`, чтобы выводить новый html только при использовании stdin в качестве входа
  :::

## 0.5.2

::: content

- Разделите требование `alt` с H006 на H013
- Добавлен необязательный файл пользовательских правил
- Добавлен `golang` в качестве опции профиля
- Исправлено форматирование игнорируемых блоков, содержащих встроенные комментарии
- Добавлен текст по умолчанию для опций `--indent` и `-e`
- Обновлены правила url для принятия #
- Исправлена кодировка файлов в ОС Windows
- Исправлен регекс для однострочных тегов шаблонов
- Исправление `blank_line_after_tag` для тегов с пробелами в начале строки

  :::

## 0.5.1

::: content

- Добавлено правило H019
- Исправлены ошибки в DJ018 и H012
  :::

## 0.5.0

::: content

- Исправлено несколько ошибок регекс-сопоставления в правилах linter
- Запрещено возвращать ошибки в игнорируемых блоках
- Добавлена возможность игнорировать блок кода из linter/formatter с тегами `{% djlint:off %}...{% djlint:on %}`.
  :::

## 0.4.9

::: content

- Исправлена ошибка [#35](https://github.com/Riverside-Healthcare/djLint/issues/35)
  :::

## 0.4.8

::: content

- Исправлена ошибка [#34](https://github.com/Riverside-Healthcare/djLint/issues/34)
  :::

## 0.4.7

::: content

- Перемещение тега `source` в однострочные теги
  :::

## 0.4.6

::: content

- Исправлена ошибка [#31](https://github.com/Riverside-Healthcare/djLint/issues/31)
  :::

## 0.4.5

::: content

- Добавлены лучшие практики в документацию
- Добавлена опция `--profile` для установки правил linter/formatter по умолчанию
- Добавлены правила linter для шаблонов jinja url
  :::

## 0.4.4

::: content

- Измените конфигурацию отступа со строки на int. `--indent 3`
  :::

## 0.4.3

::: content

- Добавлена опция cli для интервала между отступами. `--indent=" "`.
  :::

## 0.4.2

::: content

- Добавлена поддержка дополнительных пробелов после тегов с помощью опции `blank_line_after_tag`.
  :::

## 0.4.1

::: content

- Добавлена поддержка одновременной обработки нескольких файлов или папок
  :::

## 0.4.0

::: content

- Исправлено форматирование тегов django `{# ... #}` тегов
- Добавлена поддержка отступов для тегов figcaption, details и summary
- Добавлена поддержка переопределения или расширения списка исключенных путей в `pyproject.toml`.
  :::

## 0.3.9

::: content

- Обновленная обработка атрибутов
  :::

## 0.3.8

::: content

- Добавлена поддержка stdin
  :::

## 0.3.7

::: content

- Исправлено форматирование тегов `small`, `dt` и `dd`.
  :::

## 0.3.6

::: content

- Добавлена поддержка форматера для открывающих блоков Nunjucks `{%-`
  :::

## 0.3.5

::: content

- Добавлена поддержка большего количества блоков Django
- Добавлена поддержка пользовательских блоков
- Добавлена поддержка конфигурации в `pyproject.toml`
  :::

## 0.3.4

::: content

- Исправлен тег Nunjucks без пробелов в формате `-%}`
  :::

## 0.3.3

::: content

- Позволяет коротким тегам `div` быть однострочными
  :::

## 0.3.2

::: content

- Исправлено форматирование комментариев в Django
- Игнорирование форматирования текстовой области
  :::

## 0.3.1

::: content

- Обновлен регекс форматирования атрибутов
- Обновлено правило притирки W010
  :::

## 0.3.0

::: content

- Изменен код выхода на 1 в случае изменения форматирования
- Добавлена поддержка тегов `asset` в Jinja
  :::

## 0.2.9

::: content

- Обновленный регекс W018
- Удалены дублирующиеся сообщения lint
- Обновлен E001 для Handlebars
  :::

## 0.2.8

::: content

- Исправлена ошибка прогресс-бара для старой версии Click
  :::

{% endraw %}
