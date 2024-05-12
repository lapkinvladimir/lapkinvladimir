<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .container {
            position: relative;
            display: inline-block;
        }

        .text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white; /* Цвет текста */
            font-size: 24px; /* Размер текста */
            font-family: Arial, sans-serif; /* Шрифт текста */
        }
    </style>
</head>
<body>
<div class="container">
    <img src="https://community.akamai.steamstatic.com/economy/image/i0CoZ81Ui0m-9KwlBY1L_18myuGuq1wfhWSIYhY_9XEDYOMNRBsMoGuuOgceXob50kaxV_PHjMO1MHaEqgcio9CguQmoF02gxsCxpHsIv6L7PPI0cqHDXzXHwugh5rQ6GC3gxkoj52iEzImocWXNLlGEji8NUw/360fx360f" alt="Текст 1">
    <div class="text">Текст, который будет наложен на картинку</div>
</div>
</body>
</html>
