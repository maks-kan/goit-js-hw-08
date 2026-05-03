# goit-js-hw-08

**Автор:** Максим Канюка

## Опис

Домашнє завдання №8 з курсу JavaScript від GoIT — галерея зображень із
повнорозмірним переглядом у модальному вікні.

## Завдання

- **gallery.js** — створення розмітки галереї з масиву `images` через
  `insertAdjacentHTML`, делегування кліку на `ul.gallery`,
  `event.preventDefault()` для посилань, відкриття модалки
  [`basicLightbox`](https://basiclightbox.electerious.com/) з оригінальним
  зображенням за `data-source`.
- **index.html** — підключено CSS та JS бібліотеки `basicLightbox` через CDN
  (`jsdelivr`), контейнер `ul.gallery`, посилання на локальні `styles.css` і
  `gallery.js`.
- **styles.css** — стилізація галереї (grid 3 колонки з адаптивними переходами
  на 2 і 1 колонку).
