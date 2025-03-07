<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clicker Game</title>
    <link rel="stylesheet" href="style1.css">
</head>
<body>
    <header>
        <div class="logo">LOGO</div>
        <div class="menu">
            <a href="#">Home</a>
            <a href="#">Market</a>
            <a href="#">Rating</a>
        </div>
        <div class="profile" id="userMiniProfile">Tony Stark | $19,247</div>
    </header>
    <div class="stats-container">
        <div class="stats-box">
            <img src="/img/01 Images/Placeholder Square.svg" alt="">
            <div>
                <p><strong class="counterClick"></strong></p>
                <p id="totalCoinsClick">Total ClickCoins</p>
            </div>
        </div>
        <div class="stats-box">
            <img src="/img/01 Images/Placeholder Square.svg" alt="">
            <div>
                <p><strong></strong></p>
                <p id="coinsPerClick">Coins per Click</p>
            </div>
        </div>
        <div class="stats-box">
            <img src="/img/01 Images/Placeholder Square.svg" alt="">
            <div>
                <p><strong>1/sec</strong></p>
                <p>Passive Income</p>
            </div>
        </div>
    </div>
    <div class="buttonClicker">
        <button class="click-button" id="counter" onclick="clickerButton()">Ви наклікали</button>
    </div>
    <footer>
        <h3>About game</h3>
        <h3>Help Center</h3>
        <h3>Rules</h3>
    </footer>
    <script src="clicker.js"></script>
</body>
</html>
