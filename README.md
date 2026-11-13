
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Forever Love ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    background: #10090e;
    color: white;
    font-family: 'Poppins', sans-serif;
    overflow-x: hidden;
}

/* HERO */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 30px 20px;
    background:
    linear-gradient(rgba(15,5,12,.65), rgba(15,5,12,.9)),
    url("https://images.unsplash.com/photo-1518199266791-5375a83190b7?auto=format&fit=crop&w=1600&q=80");
    background-size: cover;
    background-position: center;
}

.hero-content {
    max-width: 850px;
    animation: fadeUp 1.5s ease;
}

.tag {
    color: #e9bd76;
    letter-spacing: 5px;
    font-size: 12px;
    text-transform: uppercase;
}

.hero h1 {
    font-family: 'Great Vibes', cursive;
    font-size: clamp(55px, 10vw, 110px);
    color: #ffd7e4;
    margin: 25px 0;
    text-shadow: 0 0 30px #ff4d8d;
}

.hero p {
    color: #f4dce7;
    line-height: 2;
}

.btn {
    padding: 15px 30px;
    margin: 20px 8px;
    border-radius: 40px;
    border: 1px solid #d9a85f;
    background: linear-gradient(135deg, #d9a85f, #ffcf8b);
    color: #210c17;
    font-weight: 600;
    cursor: pointer;
    transition: .3s;
}

.btn:hover {
    transform: translateY(-4px);
    box-shadow: 0 0 25px #d9a85f70;
}

section {
    padding: 80px 20px;
    text-align: center;
}

.section-title {
    font-family: 'Great Vibes', cursive;
    font-size: 55px;
    color: #ffc4d9;
    margin-bottom: 20px;
}

.subtitle {
    color: #cbb5c1;
    margin-bottom: 35px;
}

.card {
    max-width: 700px;
    margin: 25px auto;
    padding: 35px;
    border-radius: 25px;
    background: #24141e;
    border: 1px solid #654052;
    box-shadow: 0 0 40px #ff4d8d12;
}

/* CAKE */
.cake {
    font-size: 95px;
    animation: bounce 2s infinite;
    margin: 20px;
}

@keyframes bounce {
    50% {
        transform: translateY(-12px);
    }
}

/* LOVE TIMELINE */
.timeline {
    max-width: 700px;
    margin: 35px auto;
    text-align: left;
}

.timeline-item {
    position: relative;
    margin: 20px 0;
    padding: 25px 25px 25px 75px;
    background: #24141e;
    border: 1px solid #654052;
    border-radius: 20px;
    transition: .3s;
}

.timeline-item:hover {
    transform: translateX(8px);
    box-shadow: 0 0 20px #ff4d8d25;
}

.timeline-item span {
    position: absolute;
    left: 22px;
    top: 25px;
    font-size: 30px;
}

.timeline-item h3 {
    color: #ffd17e;
    margin-bottom: 8px;
}

.timeline-item p {
    color: #d9c0ce;
    line-height: 1.8;
}

/* LOVE LETTER */
.letter {
    display: none;
    text-align: left;
    line-height: 2;
    color: #f8dce8;
    margin-top: 30px;
    animation: fade .8s;
}

@keyframes fade {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.letter h3 {
    color: #ffd17e;
    font-family: 'Great Vibes', cursive;
    font-size: 38px;
    margin-bottom: 15px;
}

.signature {
    text-align: right;
    color: #ffd17e;
    font-family: 'Great Vibes', cursive;
    font-size: 35px;
    margin-top: 20px;
}

/* GIFT */
.gift {
    font-size: 100px;
    background: transparent;
    border: none;
    cursor: pointer;
    animation: bounce 2s infinite;
}

/* FLOATING HEARTS */
.heart {
    position: fixed;
    bottom: -30px;
    pointer-events: none;
    animation: floatUp 7s linear forwards;
    z-index: 99;
}

@keyframes floatUp {
    to {
        transform: translateY(-110vh) rotate(360deg);
        opacity: 0;
    }
}

/* FIREWORK HEARTS */
.firework-heart {
    position: fixed;
    pointer-events: none;
    z-index: 9999;
    animation: explode 1.5s ease-out forwards;
}

@keyframes explode {
    0% {
        transform: translate(0,0) scale(0);
        opacity: 1;
    }
    100% {
        transform: translate(var(--x),var(--y)) scale(2);
        opacity: 0;
    }
}

/* MUSIC BUTTON */
#musicBtn {
    position: fixed;
    bottom: 20px;
    right: 20px;
    z-index: 100;
    border-radius: 50%;
    width: 55px;
    height: 55px;
    background: #d9a85f;
    border: none;
    font-size: 22px;
    cursor: pointer;
    box-shadow: 0 0 20px #d9a85f50;
}

footer {
    padding: 35px;
    text-align: center;
    color: #cba9bc;
    background: #090509;
}

@keyframes fadeUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@media(max-width:600px) {
    section {
        padding: 60px 18px;
    }

    .card {
        padding: 25px;
    }

    .section-title {
        font-size: 45px;
    }
}
</style>
</head>

<body>

<!-- HERO SECTION -->
<div class="hero">
    <div class="hero-content">
        <div class="tag">A special day • A special person</div>

        <h1>Happy Birthday<br>My Love ❤️</h1>

        <p>
            To the woman who makes my world beautiful,<br>
            today is all about YOU.
        </p>

        <button class="btn" onclick="document.getElementById('birthday').scrollIntoView({behavior:'smooth'})">
            Begin Your Surprise ✨
        </button>
    </div>
</div>

<!-- BIRTHDAY SECTION -->
<section id="birthday">

    <div class="tag">My Queen • My Everything</div>

    <h2 class="section-title">Happy Birthday, My Queen 👑</h2>

    <p class="subtitle">
        Another year of your beautiful existence.
        Another year of loving you.
    </p>

    <div class="card">

        <div class="cake">🎂</div>

        <h2 style="color:#ffd17e;">Make a Wish, My Love</h2>

        <p style="margin-top:15px;line-height:2;color:#d9c0ce;">
            May your smile always shine brighter than the stars.
            May your dreams become reality.
            And may I always be beside you,
            holding your hand through everything.
        </p>

        <button class="btn" onclick="celebrate()">
            Celebrate With Me 🎉
        </button>

    </div>

</section>

<!-- OUR LOVE STORY -->
<section>

    <div class="tag">Our story • Our forever</div>

    <h2 class="section-title">Our Love Story 💞</h2>

    <p class="subtitle">
        Every little moment with you becomes a beautiful memory.
    </p>

    <div class="timeline">

        <div class="timeline-item">
            <span>✨</span>
            <h3>The Day We Met</h3>
            <p>The beginning of my favorite story — our story.</p>
        </div>

        <div class="timeline-item">
            <span>💗</span>
            <h3>Our First Smile</h3>
            <p>Your smile made my world a little brighter.</p>
        </div>

        <div class="timeline-item">
            <span>🌹</span>
            <h3>Every Moment Since</h3>
            <p>Every laugh, every talk, every memory is precious to me.</p>
        </div>

        <div class="timeline-item">
            <span>♾️</span>
            <h3>Forever Together</h3>
            <p>The best chapters of our story are still waiting to be written.</p>
        </div>

    </div>

</section>

<!-- REASONS 𝖨 𝖫𝖮𝖵𝖤 𝖸𝖮𝖴 𝖬𝖸 𝖠𝖭𝖦𝖤𝖫 -->
<section>

    <div class="tag">A little reminder</div>

    <h2 class="section-title">Reasons 𝖨 𝖫𝖮𝖵𝖤 𝖸𝖮𝖴 𝖬𝖸 𝖠𝖭𝖦𝖤𝖫  💖</h2>

    <p class="subtitle">
        Tap the button to discover a reason.
    </p>

    <div class="card">

        <div id="reasonText" style="font-size:20px;line-height:1.8;color:#f8dce8;min-height:75px;">
            You make ordinary moments feel magical. ✨
        </div>

        <button class="btn" onclick="showReason()">
            Another Reason 💕
        </button>

    </div>

</section>

<!-- ROMANTIC GIFT -->
<section>

    <div class="tag">A gift from my heart</div>

    <h2 class="section-title">Your Little Surprise 🎁</h2>

    <p class="subtitle">
        Tap the gift to open your surprise.
    </p>

    <div class="card">

        <button class="gift" id="giftBox" onclick="openGift()">🎁</button>

        <h2 id="giftMessage" style="color:#ffd17e;margin-top:20px;line-height:1.7;"></h2>

    </div>

</section>

<!-- LOVE LETTER -->
<section>

    <div class="tag">From my heart to yours</div>

    <h2 class="section-title">A Letter For You 💌</h2>

    <div class="card">

        <div style="font-size:45px;">💌</div>

        <p style="color:#e9bd76;margin:15px;">
            There is something I want to tell you...
        </p>

        <button class="btn" onclick="openLetter()">
            Open My Heart ❤️
        </button>

        <div class="letter" id="letter">

            <h3>My Dearest Love,</h3>

            Happy Birthday to the most precious person in my life.

            <br><br>

            If I could give you one thing in this world,
            it would be the ability to see yourself through my eyes.
            Only then would you understand how special you are to me.

            <br><br>

            You are my happiness on difficult days,
            my peace in a noisy world,
            and my favorite reason to smile.

            <br><br>

            I promise not a perfect life,
            but I promise to love you,
            respect you, stand beside you,
            and choose you every single day.

            <br><br>

            Happy Birthday, my beautiful wife.
            Thank you for being my home.

            <div class="signature">
                Forever Yours ❤️
            </div>

        </div>

    </div>

</section>

<!-- FINAL SURPRISE -->
<section>

    <div class="tag">One last thing...</div>

    <h2 class="section-title">You Are My Forever ❤️</h2>

    <p style="line-height:2;color:#d9c0ce;">
        Out of all the people in this world,<br>
        I would still choose you.<br>
        Today, tomorrow, and every lifetime.
    </p>

    <button class="btn" onclick="finalSurprise()">
        One Last Surprise 🎁
    </button>

    <h2 id="finalMessage"
        style="font-family:'Great Vibes';font-size:45px;color:#ffd17e;margin-top:30px;">
    </h2>

</section>

<footer>
    Made with endless love ❤️<br>
    <span style="color:#d9a85f;">Just for my beautiful wife</span>
</footer>

<!-- MUSIC -->
<button id="musicBtn" onclick="toggleMusic()">🎵</button>

<audio id="music" loop>
    <source src="love.mp3" type="audio/mpeg">
</audio>

<script>

// OPEN LOVE LETTER
function openLetter() {
    const letter = document.getElementById("letter");
    letter.style.display = "block";

    letter.scrollIntoView({
        behavior: "smooth",
        block: "center"
    });
}

// CELEBRATION
function celebrate() {
    for(let i = 0; i < 40; i++) {
        setTimeout(createHeart, i * 100);
    }

    heartFireworks();

    alert("Happy Birthday, My Love! 🎂❤️");
}

// FINAL SURPRISE
function finalSurprise() {
    document.getElementById("finalMessage").innerHTML =
        "I LOVE YOU MY ANGEL 💖";

    for(let i = 0; i < 60; i++) {
        setTimeout(createHeart, i * 80);
    }

    heartFireworks();
}

// FLOATING HEARTS
function createHeart() {
    const heart = document.createElement("div");

    heart.className = "heart";
    heart.innerHTML = ["❤️","💖","💕","💗","✨"][Math.floor(Math.random()*5)];

    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (20 + Math.random() * 25) + "px";

    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 7000);
}

setInterval(createHeart, 900);

// HEART FIREWORKS
function heartFireworks() {
    for(let i = 0; i < 80; i++) {

        const heart = document.createElement("div");

        heart.className = "firework-heart";
        heart.innerHTML = ["❤️","💖","💕","✨"][Math.floor(Math.random()*4)];

        heart.style.left = "50%";
        heart.style.top = "50%";

        heart.style.setProperty("--x", (Math.random()-0.5)*600+"px");
        heart.style.setProperty("--y", (Math.random()-0.5)*600+"px");

        document.body.appendChild(heart);

        setTimeout(() => heart.remove(), 1500);
    }
}

// REASONS I LOVE YOU
const loveReasons = [
    "Your smile is my favorite sight in the whole world. 😊",
    "Your voice makes even an ordinary day feel special. 💗",
    "You understand me in ways nobody else can. 🫶",
    "Your kindness makes me fall in love with you again. 🌷",
    "You are my peace, my happiness, and my home. 🏡",
    "Every moment with you is a memory I want to keep. ✨",
    "I love you simply because you are YOU. ❤️"
];

let reasonIndex = 0;

function showReason() {
    document.getElementById("reasonText").textContent =
        loveReasons[reasonIndex];

    reasonIndex = (reasonIndex + 1) % loveReasons.length;
}

// GIFT BOX SURPRISE
let giftOpened = false;

function openGift() {
    const box = document.getElementById("giftBox");
    const message = document.getElementById("giftMessage");

    if(!giftOpened) {

        box.textContent = "💝";

        message.textContent =
            "My greatest gift is my love for you — today and always. Happy Birthday, My Angel! ❤️";

        giftOpened = true;

        heartFireworks();

    } else {

        box.textContent = "🎁";
        message.textContent = "";
        giftOpened = false;
    }
}

// MUSIC
const music = document.getElementById("music");

function toggleMusic() {

    if(music.paused) {

        music.play().then(() => {
            document.getElementById("musicBtn").innerHTML = "🔊";
        }).catch(() => {
            alert("Please add love.mp3 in the same folder!");
        });

    } else {

        music.pause();
        document.getElementById("musicBtn").innerHTML = "🎵";
    }
}

</script>

</body>
</html>
