<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Онлайн-магазин "Чудеса Техники"</title>
    <style>
        body {
            font-family: sans-serif;
        }
        .product-image {
            max-width: 200px;
            max-height: 200px;
        }
        table {
            width: 80%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #e60d0d;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #d22626;
        }
    </style>
</head>
<body>
    <header>
        <h1>Онлайн-магазин "Чудеса Техники"</h1>
        <nav>
            <a href="#">Главная</a>
            <a href="#">Каталог</a>
            <a href="#">Контакты</a>
        </nav>
    </header>

    <audio controls src="audio.mp3" class="audio-greeting">Ваш браузер не поддерживает элемент &lt;audio&gt;.</audio>

    <section id="promo">
        <video width="640" height="360" controls src="promo.mp4">Ваш браузер не поддерживает элемент &lt;video&gt;.</video>
    </section>

    <section id="products">
        <h2>Наши товары</h2>
        <article class="product">
            <img src="product1.jpg" alt="Продукт 1" width="200" height="150" class="product-image">
            <h3>Название товара 1</h3>
            <p>Описание товара 1</p>
        </article>
        <article class="product">
            <img src="product2.jpg" alt="Продукт 2" width="200" height="150" class="product-image">
            <h3>Название товара 2</h3>
            <p>Описание товара 2</p>
        </article>
        <article class="product">
            <img src="product3.jpg" alt="Продукт 3" width="200" height="150" class="product-image">
            <h3>Название товара 3</h3>
            <p>Описание товара 3</p>
        </article>
    </section>

    <section id="product-table">
        <table>
            <caption>Список товаров</caption>
            <thead>
                <tr>
                    <th>Название</th>
                    <th>Цена</th>
                    <th>Описание</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Товар A</td>
                    <td>1000 руб.</td>
                    <td>Отличный товар!</td>
                </tr>
                <tr>
                    <td>Товар B</td>
                    <td>2000 руб.</td>
                    <td>Супер товар!</td>
                </tr>
            </tbody>
        </table>
    </section>


    <section id="feedback">
        <h2>Обратная связь</h2>
        <form action="#" method="post">
            <label for="name">Имя:</label><br>
            <input type="text" id="name" name="name" required><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>

            <label for="category">Категория запроса:</label><br>
            <select id="category" name="category">
                <option value="заказ">Заказ</option>
                <option value="вопрос">Вопрос</option>
                <option value="предложение">Предложение</option>
            </select><br><br>

            <label for="message">Сообщение:</label><br>
            <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>

            <button type="submit">Отправить</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Онлайн-магазин "Чудеса Техники"</p>
    </footer>
</body>
</html>
