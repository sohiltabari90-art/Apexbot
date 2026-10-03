<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>APEXBOT | ربات روبیکا</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Tahoma, Arial, sans-serif;
            background:
                radial-gradient(circle at top right, #6547d9 0%, transparent 35%),
                radial-gradient(circle at bottom left, #1e79c9 0%, transparent 35%),
                #080b1c;
            color: white;
            min-height: 100vh;
            text-align: center;
        }

        .container {
            width: 90%;
            max-width: 850px;
            margin: auto;
        }

        header {
            padding: 35px 0 15px;
        }

        .logo {
            display: inline-block;
            padding: 12px 28px;
            border: 1px solid rgba(255,255,255,0.25);
            background: rgba(255,255,255,0.08);
            backdrop-filter: blur(10px);
            border-radius: 50px;
            font-size: 21px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        .hero {
            padding: 85px 10px 65px;
        }

        .small-title {
            color: #aeb8ff;
            font-size: 19px;
            margin-bottom: 15px;
        }

        h1 {
            font-size: 52px;
            margin-bottom: 18px;
            background: linear-gradient(90deg, #ffffff, #9b8cff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .description {
            color: #c5c8da;
            font-size: 20px;
            line-height: 2;
            max-width: 600px;
            margin: auto auto 35px;
        }

        .button {
            display: inline-block;
            padding: 15px 32px;
            border-radius: 14px;
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            background: linear-gradient(135deg, #6856e8, #9b45d6);
            box-shadow: 0 10px 30px rgba(112, 77, 230, 0.3);
            transition: 0.2s;
        }

        .button:hover {
            transform: translateY(-3px);
        }

        .card {
            background: rgba(255,255,255,0.08);
            border: 1px solid rgba(255,255,255,0.14);
            backdrop-filter: blur(15px);
            border-radius: 24px;
            padding: 35px 25px;
            margin-bottom: 35px;
            box-shadow: 0 20px 50px rgba(0,0,0,0.2);
        }

        .card h2 {
            font-size: 28px;
            margin-bottom: 28px;
        }

        .item {
            background: rgba(255,255,255,0.06);
            border-radius: 15px;
            padding: 18px;
            margin: 13px 0;
            transition: 0.2s;
        }

        .item:hover {
            background: rgba(255,255,255,0.11);
        }

        .item-title {
            color: #a99cff;
            font-size: 15px;
            margin-bottom: 7px;
        }

        .item a {
            color: white;
            text-decoration: none;
            font-size: 19px;
            font-weight: bold;
        }

        footer {
            padding: 25px;
            color: #777d98;
            font-size: 14px;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 40px;
            }

            .hero {
                padding-top: 65px;
            }

            .description {
                font-size: 18px;
            }

            .card {
                padding: 28px 18px;
            }
        }
    </style>
</head>

<body>

    <div class="container">

        <header>
            <div class="logo">APEXBOT</div>
        </header>

        <section class="hero">

            <div class="small-title">
                ربات هوشمند روبیکا
            </div>

            <h1>
                خوش آمدید به APEXBOT
            </h1>

            <p class="description">
                یک ربات کاربردی و سرگرم‌کننده برای مدیریت بهتر گروه‌ها
                و دسترسی سریع به امکانات مختلف.
            </p>

            <a href="#support" class="button">
                ارتباط و اطلاعات بیشتر
            </a>

        </section>

        <section class="card" id="support">

            <h2>
                ارتباط با APEXBOT
            </h2>

            <div class="item">
                <div class="item-title">
                    پشتیبانی
                </div>

                <a href="https://rubika.ir/Stsosmas" target="_blank">
                    @Stsosmas
                </a>
            </div>

            <div class="item">
                <div class="item-title">
                    آیدی ربات
                </div>

                <a href="https://rubika.ir/ApoexBot" target="_blank">
                    @ApoexBot
                </a>
            </div>

            <div class="item">
                <div class="item-title">
                    کانال دستورات ربات
                </div>

                <a href="https://rubika.ir/APEXbott" target="_blank">
                    @APEXbott
                </a>
            </div>

        </section>

        <footer>
            © 2026 APEXBOT — تمامی حقوق محفوظ است
        </footer>

    </div>

</body>
</html>
