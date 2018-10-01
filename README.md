# Вёрстка одной страницы с использованием CSS и HTML

Требуется базовый уровень знаний. Паттерн фонового рисунка прикреплён. 

Все телефоны и email адреса следует сделать ссылками. При нажатии должны открываться программы для звонков или почты установленные в системе по умолчанию соответственно.

Минимальный поддерживаемый экран это с шириной 1024px. На этом разрешении не должно быть горизонтальной полосы прокрутки.

Для старта можно использовать **[генератор шаблонов](http://csstemplater.com/)**. С помощью него нужно создать скелет с правильными размерами и прибить футер к низу страницы. Это очень поможет для правильного расположения колонок страницы, если вы не знаете как по другому их сделать.

Не забыть подключить **normalize.css** в проект для сброса стилей. Его надо найти самому.

## Для фотографий людей использовать эти изображения

- [src/gallery/Man-Booker-Prize-judges-p-011.jpg](src/gallery/Man-Booker-Prize-judges-p-011.jpg)
- [src/gallery/superman_man_of_steel_star_henry_cavill_1207744.jpg](src/gallery/superman_man_of_steel_star_henry_cavill_1207744.jpg)
- [src/gallery/tumour-man-3_1510528a.jpg](src/gallery/tumour-man-3_1510528a.jpg)

### Список тегов, которые скорее всего будут использоваться:

```html
<div>
<span>
<h1>-<h6>
<article>
<p>
<header>
<footer>
<section>
<aside>
<strong>
<ul>
<li>
<a>
<nav>
<link>
<title>
<img>
```

### Список свойств стилей, которые скорее всего будут использоваться:

```text
width
height
position
display
vertical-align
margin
padding
left
top
right
bottom
white-space
text-decoration
font-style
font-weight
font-family
font-size
color
line-height
background
text-transform
transform
overflow
list-style
border
box-sizing
```

### Требуется поддержка браузеров:

- IE11+
- Chrome latest
- Firefox Latest
- Opera latest
- Safari 5+

Превью выполненного задание можно посмотреть на скриншоте [src/preview.png](./src/preview.png). Допускается, что получившийся результат может не на 100% соответствовать скриншоту.

*Превью скриншот:*

![src/preview.png](./src/preview.png)

## Настройка окружения

В проект включён статический анализ кода. Подробности настройки окружения можно почитать в [HELP.md](./blob/master/HELP.md). Но задание можно выполнить и без этого, имея только браузер и редактор кода.