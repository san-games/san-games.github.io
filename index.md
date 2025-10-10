---
title: Главная
layout: default
---

# Привет! 👋  
Добро пожаловать на **{{ site.title }}** — {{ site.description }}.

[Обо мне](./about) · [Контакты](./contact)

## Проекты
- **Project A** — кратко, ссылка → [GitHub](https://github.com/)
- **Project B** — кратко, ссылка → [Сайт](https://example.com)

## Последние записи
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — _{{ post.date | date: "%d.%m.%Y" }}_
{% endfor %}
