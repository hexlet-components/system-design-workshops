# Материалы вебинаров по системному дизайну

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

---

[![Hexlet Ltd. logo](https://raw.githubusercontent.com/Hexlet/assets/master/images/hexlet_logo128.png)](https://hexlet.io/?utm_source=github&utm_medium=link&utm_campaign=system-design-workshops)

This repository is created and maintained by the team and the community of Hexlet, an educational project. [Read more about Hexlet](https://hexlet.io/pages/about?utm_source=github&utm_medium=link&utm_campaign=system-design-workshops).

See most active contributors on [hexlet-friends](https://friends.hexlet.io/).
