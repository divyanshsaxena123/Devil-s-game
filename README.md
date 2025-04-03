<img id="mascot-image" src="images/gamer-mode.png" alt="Buff Mascot" onclick="talkMascot()">let mascotSounds = [
    "audio/flex-brain.mp3", // Replace with real files
    "audio/power-up.mp3",
    "audio/game-on.mp3"
];

function talkMascot() {
    let randomSound = mascotSounds[Math.floor(Math.random() * mascotSounds.length)];
    let mascotVoice = new Audio(randomSound);
    mascotVoice.play();
}<button onclick="playClickSound(); changeMascot()">Change Costume</button>let buttonClickSound = new Audio("audio/button-click.mp3"); // Replace with your file

function playClickSound() {
    buttonClickSound.play();
}<button id="music-btn" onclick="toggleMusic()">🔊 Mute Music</button>

<img id="mascot-image" src="images/gamer-mode.png" alt="Buff Mascot" onclick="talkMascot()"><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gamer Mode</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>🎮 Gamer Mode Activated! 🚀</h1>
    </header>

    <section class="gamer-container">
        <h2>Choose Your Gaming Style</h2>
        <img id="gamerImage" src="images/gamer1.png" alt="Gamer Mode" class="gamer-img">
        
        <button onclick="changeCostume()">Change Costume</button>
    </body {
    text-align: center;
    font-family: Arial, sans-serif;
    background-color: #1a1a2e;
    color: white;
}

h1 {
    font-size: 2em;
    margin-top: 20px;
}

.gamer-container {
    margin-top: 50px;
}

.gamer-img {
    width: 300px;
    height: auto;
    transition: transform 0.3s ease-in-out;
}

button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 1em;
    cursor: pointer;
    border: none;
    background-color: #ffcc00let gamerImages = [
    "images/gamer1.png",
    "images/gamer2.png",
    "images/gamer3.png",
    "images/gamer4.png"
];

let currentIndex = 0;

function changeCostume() {
    currentIndex = (currentIndex + 1) % gamerImages.length;
    document.getElementById("gamerImage").src = gamerImages[currentIndex];
}https://github.com/divyanshsaxena123/Devil-s-game.git
