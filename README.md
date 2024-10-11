# HTML-and-CSS-Assignment
This project showcases basic web development using HTML and CSS. It features a responsive layout with distinct sections, each containing a title and text. The design ensures consistent spacing and styling through an external CSS file, providing an organized and user-friendly experience across different devices.

### index.html
```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Задание по веб-дизайну</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="section">
        <h2 class="section-title">Раздел 1</h2>
        <p>Это текст для первого раздела. Он содержит описание.</p>
    </div>
    <div class="section">
        <h2 class="section-title">Раздел 2</h2>
        <p>Это текст для второго раздела. Он также содержит описание.</p>
    </div>
    <div class="section">
        <h2 class="section-title">Раздел 3</h2>
        <p>Это текст для третьего раздела. Продолжение описания.</p>
    </div>
</body>
</html>
### style.css
```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.section {
    border: 1px solid #000;
    margin: 20px;
    padding: 20px;
    background-color: #f9f9f9;
}

.section-title {
    text-align: right;
    margin: 0 0 10px 0;
}

@media (max-width: 768px) {
    .section {
        margin: 10px;
    }
}
