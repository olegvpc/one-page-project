# Проектная работа №2

## Проект одностраничного блочного сайта

***
Все стили распределены по файлам в соответствии с документацией [БЭМ-Nested](https://ru.bem.info/methodology/filestructure/#nested)
подгружаются директивой
```css
@import
```
## Использование тэгов:
1. Для фреймов
```html
<iframe>...</iframe>
```
2. Для секций
```html
<section>...</section>
```
3. Для цитат
```html
<blockquote>цитата</blockquote>

<cite>автор</cite>
```
## Использование анимации элементов
```css
.selector {
  position: absolute;
  top: 64px;
  right: 0;
  height: 568px;
  width: 568px;
  background-color: #2f80ed;
  z-index: 0;
  animation: rotate_element 20s linear infinite;
}

@keyframes rotate_element {
    to {
    transform: rotate(360deg);
  }
}
```
## Планы на доработку
Добавить к проекту дополнительные видео и анимацию scale(1.1) для книги Хана

### Автор:

***Ткач Олег***
