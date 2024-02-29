<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card Box</title>
    <style>
        * {
            font-family: sans-serif;
        }

        body {
            background-color: lightgray;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        .container {
            width: 45%; 
            height: 400px;
            background-color: rgb(255, 255, 255);
            margin: 40px;
            padding: 25px 0;
            box-sizing: border-box;
            box-shadow: 0 12px 12px rgb(158, 157, 157);
            display: inline-block;
            vertical-align: top; 
        }

        .container:hover {
            transform: scale(1.01);
        }

        .logo {
            width: 150px;
            margin: auto;
            display: block;
            border: 2px dotted rgb(63, 62, 62);
            border-radius: 50%;
            filter: grayscale(100%);
        }

        .logo:hover {
            filter: grayscale(0%);
        }

        .title {
            text-align: center;
            font-size: 25px;
            border-bottom: 5px solid gray;
            width: 115px;
            margin: 25px auto;
            color: rgb(87, 87, 87);
        }

        .dec {
            text-align: center;
            color: rgb(87, 87, 87);
        }

        .social {
            height: 60px;
            background-color: rgb(66, 109, 129);
            text-align: center;
        }

        .social img {
            width: 40px;
            margin: 10px;
            filter: grayscale(60%);
        }

        .social img:hover {
            transform: scale(1.1);
            opacity: 0.9;
            box-shadow: 0 12px 20px rgba(107, 107, 107, 0.2);
        }

        @media screen and (max-width: 768px) {
            .container {
                width: 90%;
                margin: 20px auto;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <img class="logo" src="images/photo.gpg.webp" alt="">
        <p class="title">Mohammad Karimi</p>
        <p class="dec">Please follow me on social media</p>
        <div class="social">
            <img src="images/whatsapp logo.png" alt="">
            <img src="images/insta.gpg.webp" alt="">
            <a href="https://www.facebook.com/AhmadPeerJan/"><img src="images/facebook.gpg.webp" alt=""></a>
        </div>
    </div>

    <div class="container">
        <img class="logo" src="images/pas 3.jpg" alt="">
        <p class="title">Malalai Amani</p>
        <p class="dec">Please follow me on social media</p>
        <div class="social">
            <img src="images/whatsapp logo.png" alt="">
            <img src="images/insta.gpg.webp" alt="">
            <a href="https://www.facebook.com/AhmadPeerJan/"><img src="images/facebook.gpg.webp" alt=""></a>
        </div>
    </div>
</body>
</html>
