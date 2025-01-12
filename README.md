<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KareBear Medical Companion</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: white;
            font-family: Arial, sans-serif;
        }

        .container {
            width: 300px;
            height: 500px;
            background-color: #a088c0;
            position: relative;
            border-radius: 20px;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .bear-ears {
            width: 300px;
            height: 150px;
            position: absolute;
            top: 0;
        }

        .ear {
            width: 80px;
            height: 80px;
            background-color: #d4c2e6;
            border-radius: 50%;
            position: absolute;
            top: 20px;
        }

        .ear.left {
            left: 40px;
        }

        .ear.right {
            right: 40px;
        }

        .bear-face {
            width: 300px;
            height: 400px;
            background-color: #d4c2e6;
            border-radius: 150px 150px 0 0;
            position: absolute;
            bottom: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .eyes {
            margin-top: 100px;
            display: flex;
            gap: 20px;
        }

        .eye {
            width: 40px;
            height: 40px;
            background-color: black;
            border-radius: 50%;
            position: relative;
        }

        .eye::after {
            content: '';
            position: absolute;
            width: 15px;
            height: 15px;
            background-color: white;
            border-radius: 50%;
            top: 5px;
            left: 5px;
        }

        .nose {
            width: 15px;
            height: 10px;
            background-color: black;
            border-radius: 50%;
            margin-top: 10px;
        }

        .button {
            width: 120px;
            height: 120px;
            background-color: #644c87;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            margin-top: 40px;
            color: white;
            text-align: center;
            cursor: pointer;
        }

        .text {
            margin-top: 30px;
            text-align: center;
            font-size: 16px;
            line-height: 1.4;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="bear-ears">
            <div class="ear left"></div>
            <div class="ear right"></div>
        </div>
        <div class="bear-face">
            <div class="eyes">
                <div class="eye"></div>
                <div class="eye"></div>
            </div>
            <div class="nose"></div>
            <div class="button">
                Lets<br>Care<br>
                <small>Click to start</small>
            </div>
            <div class="text">
                Hey, I'm KareBear<br>
                your medical companion!
            </div>
        </div>
    </div>
</body>
</html>
