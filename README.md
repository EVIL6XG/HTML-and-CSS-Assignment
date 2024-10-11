# HTML-and-CSS-Assignment
This project showcases basic web development using HTML and CSS. It features a responsive layout with distinct sections, each containing a title and text. The design ensures consistent spacing and styling through an external CSS file, providing an organized and user-friendly experience across different devices.

### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Design Assignment</title>
    <style>
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
    </style>
</head>
<body>
    <div class="section">
        <h2 class="section-title">Section 1</h2>
        <p>This is the text for the first section. It contains a description.</p>
    </div>
    <div class="section">
        <h2 class="section-title">Section 2</h2>
        <p>This is the text for the second section. It also contains a description.</p>
    </div>
    <div class="section">
        <h2 class="section-title">Section 3</h2>
        <p>This is the text for the third section. Continuation of the description.</p>
    </div>
</body>
</html>
