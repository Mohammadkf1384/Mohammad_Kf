<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <title>kf Family Membership Form</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.8/css/materialize.min.css" />
    <link href="https://fonts.googleapis.com/css?family=Markazi+Text" rel="stylesheet" />
    <link rel="stylesheet" href="css/style.css" />
    <style>
        body {
            background-image: url('https://uploadkon.ir/uploads/d4d823_24download-1-.jpg');
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            font-family: 'Markazi Text', serif;
        }

        .logo {
            display: block;
            margin: 0 auto;
            max-width: 80%;
            height: auto;
        }

        .btn {
            background-color: #ff9800;
            transition: background-color 0.3s, transform 0.3s;
        }

        .btn:hover {
            background-color: #e68900;
            transform: translateY(-2px);
        }

        .left-align {
            text-align: left;
        }

        .card {
            border-radius: 15px;
            overflow: hidden;
        }

        .moving-bar {
            position: absolute;
            top: 20px;
            /* مقدار جدید برای پایین آوردن نوار */
            left: 0;
            width: 100%;
            height: 20px;
            background-color: #134356;
            /* رنگ اولیه نوار متحرک */
            color: #fff951;
            /* رنگ متن */
            display: flex;
            align-items: center;
            justify-content: center;
            animation: move 10s linear infinite, color-change 5s linear infinite;
            /* اضافه کردن انیمیشن تغییر رنگ */
            font-size: 20px;
            border-radius: 25px;
            /* گرد کردن گوشه‌های نوار */
        }

        @keyframes move {
            0% {
                transform: translateX(100);
            }

            100% {
                transform: translateX(-100%);
            }
        }

        @keyframes color-change {
            0% {
                background-color: rgb(19, 67, 86);
                /* رنگ اولیه */
            }

            25% {
                background-color: rgb(255, 0, 0);
                /* قرمز */
            }

            50% {
                background-color: rgb(0, 255, 0);
                /* سبز */
            }

            75% {
                background-color: rgb(0, 0, 255);
                /* آبی */
            }

            100% {
                background-color: rgb(19, 67, 86);
                /* بازگشت به رنگ اولیه */
            }
        }
    </style>
</head>

<body>
    <div class="moving-bar">
        تخفیف پکیج های یک شبه پولدار شو کی اف به خاطر بلک فرایدی به مدت محدود.
    </div>
    <div class="container">
        <img class="logo" src="https://uploadkon.ir/uploads/b88b24_241639403874120.png" alt="sky" />
    </div>
    <div class="container">
        <div class="row">
            <div class="col s12 m6 offset-m3">
                <div class="card hoverable">
                    <div class="card-content grey-text text-darken-1">
                        <div class="row card-title">
                            <div class="col s12 center-align">
                                <span class="flow-text">kf login</span>
                            </div>
                        </div>
                        <div class="row">
                            <div class="input-field email-field col s12 left-align">
                                <i class="material-icons prefix">email</i>
                                <input id="email" type="email" class="validate black-text" />
                                <label for="email" class="grey-text text-lighten-1">Email</label>
                            </div>
                        </div>
                        <div class="row">
                            <form action="." class="col s12 password-form" autocomplete="nope">
                                <div class="row">
                                    <div class="input-field password-field col s12">
                                        <i class="material-icons prefix">lock</i>
                                        <input id="password" type="password" class="validate black-text" />
                                        <span id="password-strength"></span>
                                        <label for="password">Password</label>
                                    </div>
                                </div>
                                <div class="row confirm-password-row">
                                    <div class="input-field confirm-password-field col s12">
                                        <input id="confirm-password" type="password" class="validate black-text" />
                                        <label for="confirm-password">Re-enter password</label>
                                    </div>
                                </div>
                                <div class="row">
                                    <div class="col s12 center-align">
                                        <button type="submit" class="btn">Login</button>
                                    </div>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
