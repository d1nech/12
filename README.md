# Blog-customizer

**Blog-customizer** - это удобное приложение, позволяющее реализовать кастомизацию страницы блога через открывающуюся панель, а именно выбрать:

- шрифт текста,
- размер шрифта,
- цвет шрифта,
- цвет фона,
- ширина контента.

---

## Было сделано:

1. При нажатии на «стрелку» открывается сайдбар с настройками, при повторном нажатии или клике вне сайдбар закрывается.
2. При изменении настроек в сайдбаре они не применяются сразу.
3. После нажатия на «применить» стили применяются к статье.
4. При нажатии «сбросить» настройки в форме сбрасываются на начальные, которые были при открытии страницы, и стили применяются к статье.
5. Настройки устанавливаются через CSS-переменные, которые уже есть в стилях и установлены в коде в дефолтные значения.

---

## Установка и запуск

### `Требования`

Для установки и запуска проекта, необходим NodeJS v8+.

### `Установка зависимостей`

Для установки зависимостей, выполните команду:

```
$ npm i
```

### `Запуск Development сервера`

Чтобы запустить сервер для разработки, выполните команду:

```
npm start
```

---

## Форматирование и линтинг

Для запуска линтера для стилей выполните:

```
npm run stylelint
```

Для запуска линтера выполните:

```
npm run lint
```

Для запуска форматтера выполните:

```
npm run format
```
