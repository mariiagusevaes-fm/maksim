# maxim-spain — Сайт-визитка

Персональный сайт финансового консультанта в Барселоне.

## Структура репозитория

```
/
├── index.html       — главная страница (весь сайт)
├── photo.jpg        — фото (добавить позже)
└── README.md
```

## Публикация на GitHub Pages

1. Создайте репозиторий на GitHub (например, `maxim-spain`)
1. Загрузите файлы
1. Перейдите: **Settings → Pages → Source → Deploy from branch → main / root**
1. Сайт будет доступен по адресу: `https://ваш-логин.github.io/maxim-spain`

## Добавить фото

Когда будет готово фото Максима:

1. Сохраните файл как `photo.jpg` в корень репозитория
1. В `index.html` найдите блок `<!-- photo-placeholder -->` и замените:

```html
<!-- БЫЛО: -->
<div class="photo-placeholder"> ... </div>

<!-- СТАЛО: -->
<img src="photo.jpg" alt="Максим, банковский консультант в Испании" />
```

## Подключить аналитику (Google Analytics 4)

1. Создайте аккаунт на [analytics.google.com](https://analytics.google.com)
1. Получите идентификатор вида `G-XXXXXXXXXX`
1. В `index.html` найдите закомментированный блок GA и раскомментируйте его, заменив `G-XXXXXXXXXX`

## Контакты на сайте

- Telegram: [@maxim_spain](https://t.me/maxim_spain)
- WhatsApp: +7 916 760-15-15
- Email: kredit-ug@mail.ru
