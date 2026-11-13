<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sorry My Love ❤️</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Georgia, serif;
    background: linear-gradient(135deg, #250016, #720b35, #18000e);
    color: white;
    text-align: center;
    min-height: 100vh;
    overflow-x: hidden;
}

.container {
    max-width: 450px;
    margin: auto;
    padding: 35px 22px;
}

.heart {
    font-size: 75px;
    animation: heartbeat 1.2s infinite;
    margin: 25px;
}

@keyframes heartbeat {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.2); }
}

h1 {
    color: #ffb6ce;
    font-size: 34px;
    margin-bottom: 20px;
}

h2 {
    color: #ffc2d6;
    margin: 28px 0 15px;
}

p {
    font-size: 17px;
    line-height: 1.8;
    margin: 18px 0;
    color: #ffe5ed;
}

.card {
    background: rgba(255,255,255,0.09);
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 22px;
    padding: 23px;
    margin-top: 25px;
    box-shadow: 0 5px 25px rgba(0,0,0,0.2);
}

button {
    background: #ff4d79;
    border: none;
    color: white;
    padding: 15px 25px;
    border-radius: 30px;
    font-size: 17px;
    margin: 12px 5px;
    cursor: pointer;
    box-shadow: 0 5px 15px #0004;
}

button:hover {
    background: #ff82a2;
}

#message {
    display: none;
    color: #ffd4e0;
    font-size: 19px;
    line-height: 1.8;
    margin-top: 25px;
}

footer {
    margin: 40px 0 20px;
    color: #ffc2d6;
    font-style: italic;
}

.floating {
    position: fixed;
    bottom: -30px;
    animation: floatUp 7s linear infinite;
    pointer-events: none;
    opacity: 0.7;
}

@keyframes floatUp {
    to {
        transform: translateY(-110vh) rotate(360deg);
        opacity: 0;
    }
}
</style>
</head>

<body>

<div class="container">

<div class="heart">❤️</div>

<h1>I'm Sorry, My Love</h1>

<p>To the most beautiful part of my life...</p>

<div class="card">
<h2>My Dearest Love 🥺</h2>

<p>
I know I have hurt you, and I know that
just saying sorry cannot erase everything.
</p>

<p>
But please believe me, hurting you was
never what my heart wanted.
I am truly sorry for every tear,
every painful moment and every time
I made you feel less loved.
</p>
</div>

<div class="card">
<h2>Can I Tell You Something? 💗</h2>

<p>
You are not just someone I love.
You are the person with whom I imagine
my happiness, my future and my entire life.
</p>

<p>
I don't want a perfect relationship.
I want a real relationship where I learn
from my mistakes, understand your feelings
and become a better person for us.
</p>

<p>
I cannot promise that I will never make
a mistake again, but I promise to keep
trying, to listen, to understand and
to never take your love for granted.
</p>
</div>

<div class="card">
<h2>One Thing I Want You To Know ❤️</h2>

<p>
Even on the days when you are angry with me,
even when you don't want to talk to me,
my feelings for you don't disappear.
</p>

<p>
I miss your smile.
I miss our conversations.
I miss the little things that make
my world beautiful.
</p>

<p>
I don't want your forgiveness out of pressure.
I want to earn it through my actions.
</p>
</div>

<div class="card">
<h2>A Promise From My Heart 🫶</h2>

<p>
I promise to respect your feelings,
give you the time you need,
and show you through my actions
how important you are to me.
</p>

<p>
I love you, not just for the happy days,
but for all the little moments
that make you YOU.
</p>
</div>

<h2>Can You Give Me One Chance? 🥺</h2>

<p>
Not to forget everything that happened,
but to slowly make things beautiful again.
Only if and when your heart is ready.
</p>

<button onclick="showLove()">
Read My Last Message ❤️
</button>

<div id="message">
<p>
My love, I am genuinely sorry. ❤️
</p>

<p>
If I could go back and change the moments
where I hurt you, I would.
But I cannot change yesterday.
I can only make better choices today
and prove my love tomorrow.
</p>

<p>
You deserve happiness, respect, peace
and a love that makes you feel safe.
I want to give you that love.
</p>

<h2>I LOVE YOU SO MUCH ❤️</h2>

<p>
Whenever you feel ready, I would love
to hear from you. No pressure, my love.
Take care of yourself. Always.
</p>

<p>Forever wishing for your smile. 🥹</p>
</div>

<footer>
Made with all my love, just for you ❤️
</footer>

</div>

<script>
function showLove() {
    document.getElementById("message").style.display = "block";
    document.getElementById("message").scrollIntoView({
        behavior: "smooth"
    });
}

function createHeart() {
    const heart = document.createElement("div");
    heart.className = "floating";
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (15 + Math.random() * 25) + "px";
    heart.style.animationDuration = (5 + Math.random() * 5) + "s";

    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 10000);
}

setInterval(createHeart, 700);
</script>

</body>
</html>
