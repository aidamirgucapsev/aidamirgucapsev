<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Кинопортал</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1a1a1a;
            color: #b64545;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #291a1a;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #6d4747;
            padding: 10px;
        }
        nav a {
            color: #471717;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .container {
            padding: 20px;
        }
        .movie-card {
            background-color: #333;
            border-radius: 10px;
            padding: 15px;
            margin: 10px 0;
            display: flex;
            align-items: center;
        }
        .movie-card img {
            width: 100px;
            height: 150px;
            margin-right: 20px;
        }
        .movie-info h2 {
            margin: 0;
            font-size: 18px;
        }
        .movie-info p {
            margin: 5px 0;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Horrormovies</h1>
        <p>Бу испугаля? Не бойся я друг!</p>
    </header>
    <nav>
        <a href="#popular">Популярные</a>
        <a href="#genres">Жанры</a>
        <a href="#reviews">Отзывы</a>
        <a href="#about">О нас</a>
    </nav>
    <div class="container">
        <h2 id="popular">Популярные фильмы</h2>
        <div class="movie-card">
            <img src="https://avatars.mds.yandex.net/i?id=e5d85cab4611fd90c18f593081b0dd63a24bd019-4219240-images-thumbs&n=13" alt="Постер фильма">
            <div class="movie-info">
                <h2>Пила 10</h2>
                <p>Жанр: ужасы, триллер</p>
                <p>Год: 2023</p>
                <p>Рейтинг: 9.0/10</p>
            </div>
        </div>
        <div class="movie-card">
            <img src="https://avatars.mds.yandex.net/i?id=eb1c355b427d8f5f2bd59fba26013f93a173d880-10265031-images-thumbs&n=13" alt="Постер фильма">
            <div class="movie-info">
                <h2>Ужасающий 3</h2>
                <p>Жанр: ужасы</p>
                <p>Год: 2024</p>
                <p>Рейтинг: 9.5/10</p>
            </div>
        </div>
    </div>
</body>
</html>
