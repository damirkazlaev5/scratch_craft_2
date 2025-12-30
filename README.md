<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Мои игры в Scratch</title>
    <style>
        body {
            font-family: sans-serif;
            background: #12122a;
            color: #e0e0ff;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        .header {
            text-align: center;
            margin-bottom: 30px;
        }
        .logo {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid #6e54a3;
            object-fit: cover;
        }
        .site-title {
            font-size: 2em;
            color: #9370db;
            margin: 15px 0 0;
        }
        .game-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .game-card {
            background: rgba(25, 25, 50, 0.8);
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            position: relative;
            border: 1px solid rgba(110, 84, 163, 0.3);
        }
        .sticker {
            display: inline-block;
            padding: 5px 10px;
            background: linear-gradient(#8a2be2, #6a0dad);
            color: white;
            font-size: 0.75em;
            font-weight: bold;
            border-radius: 15px;
            margin-bottom: 10px;
        }
        .game-title {
            font-size: 1.2em;
            color: #d8bfff;
            margin: 10px 0;
        }
        .play-btn {
            display: inline-block;
            padding: 12px 24px;
            background: linear-gradient(#4cafd5, #2a52be);
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-weight: 600;
            margin-top: 10px;
        }
        .play-btn:hover {
            background: linear-gradient(#3a8fbf, #1e3e8a);
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <img src="https://avatars.mds.yandex.net/i?id=6c692049dec49ab54e04e39409fc3e68e7fecd97-12422696-images-thumbs&n=13" alt="Лого" class="logo">
            <h1 class="site-title">Игры в Scratch</h1>
        </header>

        <div class="game-grid">
            <!-- Игра 1 -->
            <div class="game-card">
                <div class="sticker">Сезоная!</div>
                <h2 class="game-title">Новый год Санта</h2>
                <a href="https://yandex.ru/games/app/392249" target="_blank" class="play-btn">Играть</a>
            </div>

            <!-- Игра 2 -->
            <div class="game-card">
                <div class="sticker">Круто!</div>
                <h2 class="game-title">Сделой свой кото блок</h2>
                <a href="https://scratch.mit.edu/projects/910000167/" target="_blank" class="play-btn">Играть</a>
            </div>

            <!-- Игра 3 -->
            <div class="game-card">
                <div class="sticker">Опасно!</div>
                <h2 class="game-title">Платформер ловушка</h2>
                <a href="https://scratch.mit.edu/projects/1072849145/" target="_blank" class="play-btn">Играть</a>
            </div>

            <!-- Игра 4 -->
            <div class="game-card">
                <div class="sticker">Хит!</div>
                <h2 class="game-title">Лучший банк ( Доделай )</h2>
                <a href="https://scratch.mit.edu/projects/877614345/" target="_blank" class="play-btn">Играть</a>
            </div>

            <!-- Игра 5 -->
            <div class="game-card">
                <div class="sticker">Рекомендуем!</div>
                <h2 class="game-title">Работа ключа</h2>
                <a href="https://scratch.mit.edu/projects/1120463323/" target="_blank" class="play-btn">Играть</a>
            </div>

            <!-- Игра 6 -->
            <div class="game-card">
                <div class="sticker">Полезно!</div>
                <h2 class="game-title">Обучалка для новичка</h2>
                <a href="https://scratch.mit.edu/projects/1057404004/" target="_blank" class="play-btn">Играть</a>
            </div>

            <!-- Игра 7 -->
            <div class="game-card">
                <div class="sticker">Популярно!</div>
                <h2 class="game-title">OC лучшая</h2>
                <a href="https://scratch.mit.edu/projects/964889014/" target="_blank" class="play-btn">Играть</a>
            </div>

            <!-- Игра 8 -->
            <div class="game-card">
                <div class="sticker">Топово!</div>
                <h2 class="game-title">Диплом победителя</h2>
                <a href="https://scratch.mit.edu/projects/903030636/" target="_blank" class="play-btn">Играть</a>
            </div>

            <!-- Игра 9 -->
            <div class="game-card">
                <div class="sticker">Легенда!</div>
                <h2 class="game-title">Крипта»</h2>
                <a href="https://scratch.mit.edu/projects/877335973/" target="_blank" class="play-btn">Играть</a>
            </div>

            <!-- Игра 10 -->
            <div class="game-card">
                <div class="sticker">Рекомендуем!</div>
                <h2 class="game-title">Полезно</h2>
                <a href="https://scratch.mit.edu/projects/872692714/" target="_blank" class="play-btn">Играть</a>
            </div>
        </div>
    </div>
</body>
</html>

