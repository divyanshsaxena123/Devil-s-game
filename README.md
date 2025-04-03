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
