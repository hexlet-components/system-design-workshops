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

Здесь лежат доски занятий и описания кейсов с вебинаров программы по системному дизайну. Текстовые курсы программы сюда не входят. Код учебного сервиса такси живёт отдельно, в [taxi-system](https://github.com/hexlet-components/taxi-system).

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

Excalidraw умеет положить сцену внутрь картинки. В окне «Export image» включите «Embed scene» и сохраните SVG под именем, оканчивающимся на `.excalidraw.svg`. GitHub показывает такой файл картинкой, и он же открывается обратно в редакторе перетаскиванием на [excalidraw.com](https://excalidraw.com). Одного файла хватает и читателю, и тому, кто продолжит рисовать.

Отдельно экспортировать картинку рядом со сценой не нужно. Две копии одной доски расходятся на первой же правке.
