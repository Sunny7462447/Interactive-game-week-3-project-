<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rock, Paper, Scissors Game</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="game-container">
        <h1>Rock, Paper, Scissors</h1>
        
        <div class="scoreboard">
            <div class="score-box">
                <p>Player</p>
                <span id="player-score">0</span>
            </div>
            <div class="score-box">
                <p>Computer</p>
                <span id="comp-score">0</span>
            </div>
        </div>

        <div class="choices">
            <button id="rock" class="choice-btn">🪨 Rock</button>
            <button id="paper" class="choice-btn">📄 Paper</button>
            <button id="scissors" class="choice-btn">✂️ Scissors</button>
        </div>

        <div class="messages">
            <p id="result-message">Make your move!</p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>

