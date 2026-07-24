# Unity Coffee demo — полный комплект на 5 языках

Дата: 24.07.2026 · Репозиторий: `ikartuzov-hub/unity-demo`

## Карта ссылок — 5 языков × 2 поверхности

| Язык | Демо (меню) | Инструкция (иконка на телефон) |
|---|---|---|
| PT | `/unity-demo/` | `/unity-demo/install-pt.html` |
| EN | `/unity-demo/en.html` | `/unity-demo/install-en.html` |
| RU | `/unity-demo/ru.html` | `/unity-demo/install.html` |
| ES | `/unity-demo/es.html` | `/unity-demo/install-es.html` |
| DE | `/unity-demo/de.html` | `/unity-demo/install-de.html` |

Полный адрес: `https://ikartuzov-hub.github.io` + путь.

У каждой из десяти ссылок **своё превью на своём языке** — пересланная ссылка
разворачивается карточкой с картинкой и текстом на нужном языке. Внутри страниц
язык всё равно переключается кнопкой в шапке, так что ошибиться нельзя.

Для специалиста по Армении: `https://ikartuzov-hub.github.io/unity-demo/ru.html`
и `https://ikartuzov-hub.github.io/unity-demo/install.html`

## Что заливать (25 файлов, всё в корень репо)

**Страницы (10):**
`index.html` (заменить), `ru.html`, `en.html`, `es.html`, `de.html`,
`install.html`, `install-en.html`, `install-pt.html`, `install-es.html`, `install-de.html`

**Превью (10):**
`og-pt.jpg`, `og.jpg` (заменить — старое было плоское), `og-ru.jpg`, `og-es.jpg`, `og-de.jpg`,
`og-install-ru.jpg`, `og-install-en.jpg`, `og-install-pt.jpg`, `og-install-es.jpg`, `og-install-de.jpg`

**Значки и манифест (5):**
`unity-icon.svg`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `manifest.webmanifest`

Этот README в репо не нужен.

GitHub Pages чувствителен к регистру имён — заливать ровно так, как названо.

## Как залить

github.com/ikartuzov-hub/unity-demo → **Add file** → **Upload files** →
перетащить всё разом → внизу зелёная кнопка **Commit changes** (без неё загрузка не считается) →
подождать 1–2 минуты, пока Pages пересоберётся.

⚠️ Telegram и WhatsApp кешируют превью по адресу. Старая ссылка `/unity-demo/?lang=ru`
уже закеширована без картинки — её надо прогнать через @WebpageBot. Новые адреса
(`ru.html`, `install.html` и остальные) кеша не имеют и подтянут картинку сразу.

## Что в комплекте

**Демо (`index.html`)**
- Конструктор напитка: основа → объём → молоко → сироп → добавка, цена пересчитывается
  мгновенно, стакан наливается, готовый напиток падает в корзину со своим названием
  на языке интерфейса. Плюс прежняя анимация «телефон → чашка».
- Значок на телефон, manifest, расширенные OG-теги, понимает `theme=night/day`.

**Инструкция (`install.html` и языковые версии)**
- Шапка: значок Unity, название, круглые кнопки языка (5) и день/ночь.
- Вкладки iPhone / Android с автоопределением платформы, по 4 шага.
- Кнопка «Открыть Unity Coffee» — язык и тема едут в демо.
- Поделиться / скопировать ссылку / QR-код (на десктопе QR открывается сразу).
- Футер: © год · SeedWave → Хаб · Igor Kartuzov → LinkedIn, отступ 56px под жестовую зону.

## Осталось за кадром

- `flyer.html` (листовка «Подробнее») — нет ни у Моти, ни у Unity.
- Карточка в Хабе ×5 языков и деп-линк `t.me/SeedWaveBot?start=unity`.
- Блок про субсидии в футере демо говорит про Portugal 2030 — для армянского рынка
  его надо убрать или заменить на местную программу.
