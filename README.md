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

        html,
        body {
            width: 100%;
            min-height: 100%;
        }

        body {
            min-height: 100vh;

            background:
                radial-gradient(
                    circle at 50% 35%,
                    rgba(250, 204, 21, 0.10),
                    transparent 35%
                ),
                #0a0a0a;

            color: white;
            font-family: Arial, Helvetica, sans-serif;

            display: flex;
            align-items: center;
            justify-content: center;

            padding: 25px;
        }

        .container {
            width: 100%;
            max-width: 560px;
            text-align: center;
        }

        .logo {
            width: 105px;
            height: 105px;

            margin: 0 auto 28px;

            display: flex;
            align-items: center;
            justify-content: center;

            background: #facc15;
            color: #111;

            border-radius: 28px;

            font-size: 52px;
            font-weight: 900;

            box-shadow:
                0 0 25px rgba(250, 204, 21, 0.35),
                0 0 70px rgba(250, 204, 21, 0.12);
        }

        h1 {
            font-size: 58px;
            font-weight: 900;
            letter-spacing: -3px;

            margin: 0 0 12px;
        }

        .description {
            color: #999;
            font-size: 19px;

            margin-bottom: 28px;
        }

        .online {
            display: inline-flex;
            align-items: center;
            gap: 11px;

            padding: 12px 20px;

            border-radius: 50px;

            background: rgba(250, 204, 21, 0.06);
            border: 1px solid rgba(250, 204, 21, 0.45);

            color: #facc15;

            font-size: 16px;
            font-weight: 600;

            margin-bottom: 30px;
        }

        .online-dot {
            width: 10px;
            height: 10px;

            border-radius: 50%;

            background: #facc15;

            box-shadow: 0 0 14px #facc15;
        }

        .buttons {
            width: 100%;
        }

        .button {
            width: 100%;
            min-height: 68px;

            display: flex;
            align-items: center;
            justify-content: center;

            border-radius: 18px;

            text-decoration: none;

            font-size: 18px;
            font-weight: 800;

            background: #facc15;
            color: #111;

            border: 1px solid #facc15;

            box-shadow:
                0 5px 25px rgba(250, 204, 21, 0.12);

            transition: 0.2s ease;
        }

        .button:hover {
            transform: translateY(-3px);

            background: #fde047;
            border-color: #fde047;

            box-shadow:
                0 10px 35px rgba(250, 204, 21, 0.18);
        }

        .icon {
            margin-right: 12px;
            font-size: 24px;
        }

        @media (max-width: 600px) {

            body {
                padding: 20px;
            }

            .logo {
                width: 90px;
                height: 90px;

                border-radius: 25px;

                font-size: 45px;

                margin-bottom: 22px;
            }

            h1 {
                font-size: 50px;
            }

            .description {
                font-size: 17px;
            }

            .button {
                min-height: 64px;
                font-size: 17px;
            }
        }
    </style>
</head>

<body>

    <main class="container">

        <div class="logo">M</div>

        <h1>Mirage</h1>

        <div class="description">
            Выбери нужный раздел ниже
        </div>

        <div class="online">
            <span class="online-dot"></span>
            1000+ активных пользователей
        </div>

        <div class="buttons">

            <a
                class="button"
                href="https://t.me/Kamado002_bot?start=xaFVutS2AxA"
                target="_blank"
                rel="noopener noreferrer"
            >
                <span class="icon">➤</span>
                Бот для сноса
            </a>

        </div>

    </main>

</body>
</html>