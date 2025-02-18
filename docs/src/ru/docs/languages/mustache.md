---
title: Mustache Template Linter and Formatter
keywords: mustache, djlint, mustache template linter, mustache template formatter, format mustache templates
description: djLint - это линтер шаблонов mustache и форматировщик шаблонов mustache! Используйте преимущества профиля предварительной сборки при линтинге и форматировании ваших шаблонов с помощью djLint.
tool: handlebars
---

# {{ title }}

{{ description }}

**[Что такое Mustache?](http://mustache.github.io/mustache.5.html)**

#### Использование командной строки

```bash
djlint /path/to/templates --profile={{ tool }}
```

#### Или используйте файл конфигурации

Настройте djLint в вашем проекте `pyproject.toml`.

```toml
[tool.djlint]
profile="{{ tool }}"
```

<div class="box notification is-info is-light">
    <span class="icon is-large"><i class="fas fa-2x fa-arrow-circle-right"></i></span><div class="my-auto ml-3 is-inline-block"><a href="/ru/docs/configuration/">Ознакомьтесь с руководством по настройке, чтобы узнать обо всех возможностях!</a></div>
</div>
