<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Merry Christmas Ashwin</title>
    <style>
        body {
            background-color: #001f3f;
            margin: 0;
            overflow: hidden;
        }

        .tree {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 0;
            height: 0;
            border-left: 50px solid transparent;
            border-right: 50px solid transparent;
            border-bottom: 100px solid #008000;
        }

        .lights {
            position: absolute;
            top: 25%;
            left: 50%;
            transform: translateX(-50%);
            width: 10px;
            height: 10px;
            background-color: #ffcc00;
            border-radius: 50%;
            animation: twinkle 1s infinite alternate;
        }

        @keyframes twinkle {
            0% {
                opacity: 1;
            }
            100% {
                opacity: 0.5;
            }
        }

        .greeting {
            position: absolute;
            top: 70%;
            left: 50%;
            transform: translateX(-50%);
            font-family: 'Arial', sans-serif;
            font-size: 24px;
            color: #ffffff;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="tree"></div>
    <div class="lights" style="top: 25%; left: 40%;"></div>
    <div class="lights" style="top: 30%; left: 60%;"></div>
    <div class="lights" style="top: 35%; left: 30%;"></div>
    <div class="lights" style="top: 40%; left: 70%;"></div>
    <div class="lights" style="top: 45%; left: 50%;"></div>
    <div class="greeting">Vrolijk Kerstfeest, Ashwin! 🎄</div>
</body>
</html>
