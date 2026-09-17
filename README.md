<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mirage</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            background: #0a0a0a;
            color: white;
            font-family: Arial, Helvetica, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 520px;
            text-align: center;
        }

        .logo {
            width: 75px;
            height: 75px;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: #facc15;
            color: #111;
            border-radius: 22px;
            font-size: 32px;
            font-weight: 900;
            box-shadow: 0 0 40px rgba(250, 204, 21, 0.25);
        }

        h1 {
            font-size: 55px;
            font-weight: 900;
            margin-bottom: 10px;
        }

        .description {
            color: #999;
            font-size: 16px;
            margin-bottom: 25px;
        }

        .online {
            display: inline-flex;
            align-items: center;
            gap: 9px;
            padding: 10px 16px;
            border-radius: 50px;
            background: rgba(250, 204, 21, 0.08);
            border: 1px solid rgba(250, 204, 21, 0.3);
            color: #fde047;
            font-size: 14px;
            margin-bottom: 25px;
        }

        .online-dot {
            width: 8px;
            height: 8px;
            border-radius: 50%;
            background: #facc15;
            box-shadow: 0 0 10px #facc15;
        }

        .buttons {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .button {
            width: 100%;
            min-height: 58px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 16px;
            text-decoration: none;
            font-size: 16px;
            font-weight: 700;
            transition: 0.2s;
            border: 1px solid #292929;
            background: #151515;
            color: white;
        }

        .button:hover {
            transform: translateY(-2px);
            border-color: #facc15;
        }

        .button-main {
            background: #facc15;
            color: #111;
            border-color: #facc15;
        }

        .button-main:hover {
            background: #fde047;
        }

        .footer {
            margin-top: 25px;
            color: #666;
            font-size: 13px;
        }

        .footer span {
            color: #facc15;
        }
    </style>
</head>

<body>

    <div class="container">

        <div class="logo">M</div>

        <h1>Mirage</h1>

        <div class="description">
            Выбери нужный раздел ниже
        </div>

        <div class="online">
            <div class="online-dot"></div>
            1000+ активных пользователей
        </div>

        <div class="buttons">

            <a class="button button-main" href="https://t.me/" target="_blank">
                🔹 Перейти в Telegram
            </a>

            <a class="button" href="https://github.com/" target="_blank">
                🔹 GitHub
            </a>

        </div>

        <div class="footer">
            © 2026 <span>Mirage</span>
        </div>

    </div>

</body>
</html>