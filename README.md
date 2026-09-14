<div align="center">

<a href="https://hexlet.io/?utm_source=github&utm_medium=link&utm_campaign=system-design-workshops">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hexlet/brand-assets/master/images/svg/hexlet_wordmark_white_rus.svg">
        <img src="https://raw.githubusercontent.com/Hexlet/brand-assets/master/images/svg/hexlet_wordmark_primary_rus.svg" alt="Хекслет" height="64">
    </picture>
</a>

# Материалы вебинаров по системному дизайну

</div>

Материалы создаёт и поддерживает команда [Хекслета](https://hexlet.io/?utm_source=github&utm_medium=link&utm_campaign=system-design-workshops), образовательного проекта.

Здесь лежат доски занятий и описания кейсов с вебинаров программы по системному дизайну.

## Раскладка

Каждое занятие получает свой каталог в `workshops/`. Имя начинается с номера, кратного десяти, поэтому новое занятие вставляется между соседними без переименования остальных.

```text
workshops/
  00-example/
    README.md
    board.excalidraw.svg
```

Каталог `00-example` показывает форму и в занятиях не используется. Новое занятие заводится копией этого каталога.

## Доска хранится одним файлом

Экспортированный SVG несёт внутри себя исходник доски, поэтому картинку и исходник не приходится хранить по отдельности. GitHub показывает такой файл картинкой, а [excalidraw.com](https://excalidraw.com) открывает его обратно на редактирование, если перетащить файл в окно.

Сохраняйте доску через «Export image» с включённым «Embed scene», а имя файла заканчивайте на `.excalidraw.svg`.

Вторую копию доски рядом класть не нужно. Две копии расходятся на первой же правке.
