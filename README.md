# Shreyaaa
Maan jaao
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For Shreeya 💗</title>
<style>
    body {
        margin: 0;
        padding: 0;
        font-family: 'Segoe UI', sans-serif;
        background: linear-gradient(#fff, #ffe6f0);
        overflow: hidden;
    }

    .watermark {
        position: fixed;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 100px;
        color: #ffb6c1;
        opacity: 0.3;
        z-index: 0;
        font-weight: bold;
    }

    .card {
        position: relative;
        max-width: 700px;
        margin: 80px auto;
        background: white;
        padding: 30px;
        border-radius: 20px;
        box-shadow: 0 10px 30px rgba(255,105,180,0.3);
        z-index: 1;
        color: #c2185b;
        font-size: 18px;
        line-height: 1.6;
    }

    .title {
        text-align: center;
        font-size: 26px;
        margin-bottom: 20px;
        color: #ff1493;
        font-weight: bold;
    }

    .heart, .choco {
        position: absolute;
        font-size: 24px;
        animation: float 6s linear infinite;
        opacity: 0.8;
    }

    @keyframes float {
        from { transform: translateY(100vh); }
        to { transform: translateY(-10vh); }
    }
</style>
</head>
<body>

<div class="watermark">shreeya</div>

<div class="card">
    <div class="title">💗 Meri Shreya 💗</div>
    Mujhse jo bhi galti hui, uske liye dil se maafi chahta hoon.<br><br>
    Mera intention kabhi bhi tumhe hurt karna nahi tha.<br><br>
    Shayad lafzon mein kami reh gayi, par pyaar mein kabhi nahi.<br><br>
    Tumhari narazgi mere liye saza jaisi hai,<br>
    kyunki tumhari muskaan hi meri sabse badi taqat hai.<br><br>
    Main perfect nahi hoon, par tumhare liye behtar banne ki<br>
    poori koshish karta hoon… har roz, har pal.<br><br>
    Please ek mauka de do apne is pagal ko.<br><br>
    Tumhari ek muskaan ke liye main hazaar baar sorry bol sakta hoon.<br><br>
    <b>I’m really sorry ❤️<br>
    I love you, hamesha.</b>
</div>

<script>
function createFloating(symbol, className) {
    const el = document.createElement("div");
    el.className = className;
    el.innerHTML = symbol;
    el.style.left = Math.random() * 100 + "vw";
    el.style.animationDuration = (4 + Math.random() * 4) + "s";
    document.body.appendChild(el);

    setTimeout(() => el.remove(), 7000);
}

setInterval(() => createFloating("❤️", "heart"), 500);
setInterval(() => createFloating("🍫", "choco"), 900);
</script>

</body>
</html>
