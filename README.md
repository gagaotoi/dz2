дз 1 дз 2


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
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мистер Бист (Джимми Дональдсон) - Мини-биография</title>
    <style>
        body {
            font-family: sans-serif;
            line-height: 1.6;
        }
        ol, ul {
            margin-left: 20px;
        }
    </style>
</head>
<body>

    <!-- Основной заголовок: Имя человека -->
    <h1>Мистер Бист (Джимми Дональдсон)</h1>

    <!-- Раздел: Ранние годы -->
    <h2>Ранние годы</h2>
    <p>Джимми Дональдсон, более известный как Мистер Бист, родился <strong>7 мая 1998 года</strong> в Гринвилле, Северная Каролина. <i>С юных лет он проявлял предпринимательский дух</i>, создавая различные небольшие компании и экспериментируя с разными онлайн-платформами.  Изначально он приобрел популярность, создавая видеоролики на игровых каналах, в основном сосредотачиваясь на <u>прохождениях игр и челленджах</u>. Его ранние видео, хотя и были простыми в плане производства, демонстрировали его стремление к креативному и уникальному контенту.</p>

    <!-- Раздел: Восхождение к славе и карьера -->
    <h2>Восхождение к славе и карьера</h2>
    <p>Канал Мистера Биста действительно взлетел благодаря его все более амбициозным и экстравагантным видеороликам. <strong>Его фирменный стиль включает в себя масштабные трюки, дорогие раздачи и сложные челленджи</strong>. Он известен тем, что постоянно расширяет творческие границы и вкладывает значительные суммы денег в свои проекты. Его успех можно объяснить его искренним энтузиазмом, уникальной природой его контента и продуманными маркетинговыми стратегиями. Он постоянно переопределяет то, что возможно в рамках YouTube.</p>

    <ol>
        <li>2012 год: Запуск своего YouTube-канала.</li>
        <li>2017 год: Начало создания масштабных видеороликов с челленджами.</li>
        <li>2019 год: Запуск MrBeast Burger, виртуальной сети ресторанов.</li>
        <li>2020-настоящее время: Расширение на другие проекты, включая TeamSeas и различные благотворительные инициативы.</li>
    </ol>

    <!-- Раздел: Достижения и влияние -->
    <h2>Достижения и влияние</h2>
    <ul>
        <li>Один из самых популярных ютуберов в мире.</li>
        <li>Успешный запуск нескольких успешных бизнес-проектов.</li>
        <li>Привлечение значительного внимания и средств для различных благотворительных целей.</li>
        <li>Вдохновил многочисленных других создателей своим инновационным и увлекательным контентом.</li>
        <li>Создал новый стиль контента на YouTube, подчеркивающий масштаб и филантропию.</li>
    </ul>


    <!-- Раздел: Дополнительная информация -->
    <h2>Дополнительная информация</h2>
    <p>Узнайте больше о Мистере Бисте:</p>
    <ul>
        <li><a href="https://www.youtube.com/@MrBeast" target="_blank">YouTube-канал Мистера Биста</a></li>
        <li><a href="https://ru.wikipedia.org/wiki/MrBeast" target="_blank">Википедия (русский)</a></li>
        <!-- Добавьте другие релевантные ссылки здесь -->
    </ul>

</body>
</html>
