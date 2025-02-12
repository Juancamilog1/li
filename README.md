<!DOCTYPE html>
<html lang="en">
<head>  
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title> te gustaria estar conmigo para siempre? 😍😍</title>
</head>
<body>
    <div class="container">
        <div class="tenor-gif-embed" data-postid="25854521" data-share-method="host" data-aspect-ratio="1" data-width="100%"><a href="https://tenor.com/view/tkthao219-peach-goma-love-gif-25854521">Tkthao219 Peach Sticker</a>from <a href="https://tenor.com/search/tkthao219-stickers">Tkthao219 Stickers</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
        <h1> estarias conmigo sin importar que? 🥰</h1>
        <p>eres una de las personas que mas adoro</p>
        <div class="btn">
            <a href="si.html">SI</a>
            <a href="no1.html">NO</a>
        </div>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Piensatelo...</title>
</head>
<body>
    <div class="container">
        <div class="tenor-gif-embed" data-postid="8754256510208746708" data-share-method="host" data-aspect-ratio="0.948276" data-width="100%"><a href="https://tenor.com/view/begging-cat-cat-cute-sweet-gif-8754256510208746708">Begging Cat Cat Sticker</a>from <a href="https://tenor.com/search/begging+cat-stickers">Begging Cat Stickers</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
        <h1>100% seguraaaa? 🥶🥹  </h1>
        <p>espero no te estes equivocando</p>
        <div class="btn">
            <a href="si.html">SI</a>
            <a href="no2.html">NO</a>
        </div>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Seras mia...</title>
</head>
<body>
    <div class="container">
        <div class="tenor-gif-embed" data-postid="18655731" data-share-method="host" data-aspect-ratio="1.0356" data-width="100%"><a href="https://tenor.com/view/yes-gif-18655731">Yes Sticker</a>from <a href="https://tenor.com/search/yes-stickers">Yes Stickers</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
        <h1>estaras conmigo viva o muerta jajajjajaj 😈  </h1>
        <p>preparate ya no hay vuelta atras</p>
        <div class="btn">
            <a href="si.html">SI</a>
            <a href="#" id="btn-random">NO</a>
        </div>
    </div>
    <script src="scrip.js"></script>
</body>
</html>

const btnNo = document.querySelector("#btn-random")

function moverAleatoriamente(btn) {
    btn.style.position = "absolute";
    btn.style.fontWeight = "bolder";
    btn.style.top = Math.floor(Math.random() * 90 + 5) + "%"
    btn.style.left = Math.floor(Math.random() * 90 + 5) + "%"
}

btnNo.addEventListener("mouseenter", function (e) {
    moverAleatoriamente(e.target)
})

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}

body {
    position: relative;
    width: 100%;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgba(46, 66, 216, 0.267);
}

.container {
    display: flex;
    flex-direction: column;
    text-align: center;
    align-items: center;
    gap: 20px;
    max-width: 500px;
    margin: 20px;
}

.container .tenor-gif-embed {
    display: flex;
    max-width: 200px;
}

.container .btn {
    display: flex;
    gap: 25px;
}

.btn a {
    text-decoration: none;
    color: #111;
    background: #fff;
    padding: 10px 25px;
    border-radius: 8px;
    box-shadow: 0.5rem 1rem 3rem hsl(0, 0, 0,0.3);

}
