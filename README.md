<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Forever Love ❤️</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400;500;600&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: #10090e;
    color: white;
    font-family: 'Poppins', sans-serif;
    overflow-x: hidden;
}

html {
    scroll-behavior: smooth;
}

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
    font-size: 16px;
}

.btn {
    display: inline-block;
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

.btn-outline {
    background: transparent;
    color: white;
    border: 1px solid #ffb7d0;
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
    max-width: 650px;
    margin: auto;
    padding: 35px;
    border-radius: 25px;
    background: #24141e;
    border: 1px solid #654052;
    box-shadow: 0 0 40px #ff4d8d12;
}

.cake {
    font-size: 95px;
    animation: bounce 2s infinite;
    margin: 20px;
}

@keyframes bounce {
    50% { transform: translateY(-12px); }
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 20px;
    max-width: 950px;
    margin: auto;
}

.gallery img {
    width: 100%;
    height: 320px;
    object-fit: cover;
    border-radius: 20px;
    border: 1px solid #75445c;
    transition: .4s;
}

.gallery img:hover {
    transform: scale(1.03);
    box-shadow: 0 0 25px #ff4d8d40;
}

.letter {
    display: none;
    text-align: left;
    line-height: 2;
    color: #f8dce8;
    margin-top: 30px;
    animation: fade .8s;
}

@keyframes fade {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}

.letter h3 {
    color: #ffd17e;
    font-family: 'Great Vibes', cursive;
    font-size: 38px;
    margin-bottom: 15px;
}

.letter .signature {
    text-align: right;
    color: #ffd17e;
    font-family: 'Great Vibes', cursive;
    font-size: 35px;
    margin-top: 20px;
}

footer {
    padding: 35px;
    text-align: center;
    color: #cba9bc;
    background: #090509;
}

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

@media(max-width:600px) {
    section { padding: 60px 18px; }
    .card { padding: 25px; }
    .gallery img { height: 260px; }
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

        <button class="btn" onclick="document.getElementById('birthday').scrollIntoView()">
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

<!-- PHOTO SECTION -->

<section>

    <div class="tag">Our beautiful memories</div>

    <h2 class="section-title">My Favorite Person 📸</h2>

    <p class="subtitle">
        Every memory with you is my favorite.
    </p>

    <div class="gallery">

        <img src="index.pic/WhatsApp Image 2026-11-11 at 8.11.05 PM (1).jpeg" alt="Our memory 1">

        <img src="index.pic/WhatsApp Image 2026-11-11 at 8.11.05 PM (2).jpeg" alt="Our memory 2">

        <img src="index.pic/WhatsApp Image 2026-11-11 at 8.11.05 PM.jpeg" alt="Our memory 3">

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

            I promise a perfect life,
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

<!-- MUSIC BUTTON -->

<button id="musicBtn" onclick="toggleMusic()" aria-label="Play or pause music">🎵</button>

<!-- ROMANTIC BACKGROUND MUSIC -->

<audio id="music" loop preload="auto">
    <source src="./love.mp3" type="audio/mpeg">
    Your browser does not support audio.
</audio>

<script>

function openLetter() {
    const letter = document.getElementById("letter");

    letter.style.display = "block";

    letter.scrollIntoView({
        behavior: "smooth",
        block: "center"
    });
}

function celebrate() {
    for(let i = 0; i < 40; i++) {
        setTimeout(createHeart, i * 100);
    }

    alert("Happy Birthday, My Love! 🎂❤️");
}

function finalSurprise() {
    document.getElementById("finalMessage").innerHTML =
        "𝙸 𝙻𝙾𝚅𝙴 𝚈𝙾𝚄 𝙼𝚈 𝙰𝙽𝙶𝙴𝙻 💖";

    for(let i = 0; i < 60; i++) {
        setTimeout(createHeart, i * 80);
    }
}

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


</script>

</body>
</html>
