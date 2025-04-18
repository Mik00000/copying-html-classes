# 📋 Extract SCSS Classes

> 🇺🇦 Українська версія нижче ⬇

An extension for Visual Studio Code that extracts all CSS classes from HTML or JSX code and formats them into **nested SCSS**. The result is automatically copied to the clipboard.

---

## ⚙️ Features

- Supports standard HTML (`class="..."`)
- Supports JSX/React (`className="..."`, template strings, nested components)
- Generates **nested** SCSS
- Copies the result to clipboard
- Displays the number of extracted SCSS blocks

---

## 🖱️ How to Use

1. Open an HTML or JSX/TSX file in VS Code.
2. Open the Command Palette (`Ctrl+Shift+P` or `F1`) and run:
3. SCSS will be generated and copied to your clipboard.

---

## 💡 Example

HTML:

```html
<div class="wrapper">
<header class="header">
 <h1 class="title">Title</h1>
</header>
</div>
```

SCSS:

```scss
.wrapper {
  .header {
    .title {
    }
  }
}
```
## Dependencies

    cheerio

    @babel/parser

    @babel/traverse
Author

Created with ❤️ by [Mrhopro]

🇺🇦 Витягування SCSS класів

Розширення для Visual Studio Code, яке витягує всі CSS-класи з HTML або JSX-коду та формує з них вкладену структуру SCSS. Результат автоматично копіюється в буфер обміну.

 ## ⚙️ Можливості

 - Підтримка звичайного HTML (class="...")
 -  Підтримка JSX/React (className="...", шаблонні строки, вкладені компоненти)
 - Генерація SCSS з вкладеністю
 - Копіювання результату у буфер обміну
 - Повідомлення про кількість згенерованих SCSS-блоків
 ## 🖱️ Як користуватись

 1. Відкрий HTML або JSX/TSX файл у VS Code.
 2. Відкрий палітру команд (`Ctrl+Shift+P` або `F1`) і введи:
 ```Extract SCSS from HTML/JSX```
 3. SCSS код буде згенеровано і скопійовано в буфер обміну.

 ## 💡 Приклад
 HTML:

```html
<div class="wrapper">
<header class="header">
 <h1 class="title">Title</h1>
</header>
</div>
```

SCSS:

```scss
.wrapper {
  .header {
    .title {
    }
  }
}
```

Автор

Створено з ❤️ [Mrhopro]