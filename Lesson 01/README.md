# Lesson 01 - Introduction

Biz mana bu tillarni o'rganyapmiz:

- **HTML**: Hyper-Text Markup Language
- **CSS**: Cascading Style Sheet
- **JavaScript**
- **React.js**
- **Tailwind CSS**

## HTML

```html
<html>
  <head>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
  </head>
  <body>
    <h1>Hello world</h1>
  </body>
</html>
```

- **head**: sayt haqida ma'lumotlarni yozish uchun. CSS va JavaScript bog'lash uchun.
- **body**: barcha elementlarni saytda ko'rsatish uchun.
- **defer**: JavaScript yurishidan oldin HTMLni to'liq yuklab olish usuli.

## CSS

CSS - saytning dizayni.

```css
body {
  background-color: black;
} 

h1 {
  color: white;
}
```

## JavaScript

JavaScript - saytning funksiyasi.

```js
const olmaNarxi = 5000;

function narxniAniqlash(kg) {
  return olmaNarxi * kg;
}

narxniAniqlash(5) // 5000 * 5 = 25000
```