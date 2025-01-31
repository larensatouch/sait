# sait
sait
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Дракончик Льодовий: Подорож у Мрії</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Дракончик Льодовий: Подорож у Мрії</h1>
    </header>

    <main>
        <section class="intro">
            <h2>Про гру</h2>
            <p>Допоможи дракончику Зірці відновити магію світу, пройшовши через небезпечні льодові гірки і лавові пастки!</p>
        </section>

        <section class="game-controls">
            <h2>Як грати?</h2>
            <ul>
                <li>Натискайте <strong>↑</strong> для руху вгору.</li>
                <li>Натискайте <strong>↓</strong> для руху вниз.</li>
                <li>Натискайте <strong>→</strong> для руху вправо.</li>
                <li>Натискайте <strong>←</strong> для руху вліво.</li>
            </ul>
        </section>

        <section class="start-game">
            <button id="startGameButton">Почати гру</button>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Дракончик Льодовий</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f8ff;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #1e90ff;
    color: white;
    text-align: center;
    padding: 20px;
}

h1 {
    font-size: 2.5rem;
}

main {
    padding: 20px;
}

.intro {
    background-color: #e6f7ff;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 8px;
}

.intro h2 {
    font-size: 1.5rem;
}

.game-controls {
    background-color: #f2f2f2;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 8px;
}

.game-controls ul {
    list-style-type: none;
}

.game-controls li {
    margin-bottom: 10px;
}

.start-game {
    text-align: center;
}

button {
    background-color: #1e90ff;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 1.2rem;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background-color: #4682b4;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #1e90ff;
    color: white;
}

document.getElementById('startGameButton').addEventListener('click', function() {
    alert('Гра почалася! (Це просто тестова кнопка)');
    // Тут можна додати код для запуску гри, наприклад, редирект на сторінку гри або ініціалізацію гри.
});


