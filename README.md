<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Серикбаев Аманияз</title>
    <link rel="icon" href="https://otkritkis.com/wp-content/uploads/2022/06/mwrkn.gif">
</head>

<body>
    <header>
        <section class="menu_">
            <div class="menu">
                <div class="row">
                    <div class="logo">
                        <h1><a href="">Advance<b>4</b>Web </a></h1>
                    </div>
                    <div class="menu-section">
                        <ul>
                            <li><a href=""><i>О компании</i></a></li>
                            <li>|</li>
                            <li><a href=""><i>Услуги</i></a></li>
                            <li>|</li>
                            <li><a href=""><i>Цены</i></a></li>
                            <li>|</li>
                            <li><a href="" id="red"><i>Портфолио</i></a></li>
                            <li>|</li>
                            <li><a href=""><i>Контакты</i></a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <section class="info">
            <div class="info_">
                <p><i>Дизайн студия "Advance Web" - это команда<br>профессионалов среди компьютерного дизайна
                        и<br>веб-программирования</i></p>
            </div>
            <div class="contacts">
                <ul>
                    <li>
                        <h1><i><b>8 (905)</b> 13-22-111</i></h1>
                    </li>
                    <li>
                        <a href="">Amaniaz2006@mail.ru</a>
                    </li>
                </ul>
            </div>
        </section>
        <section class="images">
            <img src="https://luxe-host.ru/wp-content/uploads/2/d/2/2d2e9c906cec681b2b5e5532c233aa4e.png" alt=""
                width="230" id="imgpos1">
            <img src="http://bboom.pro/wp-content/uploads/2021/06/Razrabotka-saitov-3-1.jpg" alt="" width="230"
                id="imgpos2">
            <img src="https://ru.seaicons.com/wp-content/uploads/2015/06/Sites-2-icon.png" alt="" width="230"
                id="imgpos3">
            <img src="https://global-uploads.webflow.com/60a35497ea15cf45782248b1/6168df92ff22145b35f938f4_30%20%D1%81%D0%B0%D0%B9%D1%82%D0%BE%D0%B2.png"
                alt="" width="230" id="imgpos4">
            <img src="https://вип-сервис.рф/images/uslugi/dizajn-and-programmirovanie.jpg" alt="" width="230"
                id="imgpos5">
        </section>
    </header>
</body>
<style>
    body,
    html {
        padding: 0;
        margin: 0;
    }

    #red {
        color: red;
    }

    .menu-section {
        width: 32%;
    }

    .menu-section ul {
        display: flex;
        justify-content: space-between;
    }

    .menu-section a {
        color: white;
    }

    .menu-section li {
        color: white;
        transition-duration: 0.5s;
    }

    .menu-section li:hover {
        letter-spacing: 2px;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    .menu {
        background-color: black;
        padding: 20px 0px;
    }

    .row {
        display: flex;
        justify-content: space-between;
        width: 75%;
        margin: auto;
    }

    header {
        background-color: rgba(10, 10, 10, 0.886);
        padding-bottom: 70px;
    }

    body {
        /* background-color: rgba(10, 10, 10, 0.886); */
    }

    a {
        text-decoration: none;
    }

    .logo h1 {
        margin: 0;
    }


    .logo a {
        color: rgba(255, 255, 255, 0.934);
        font-family: Arial;
        font-size: 50px;
        transition-duration: 0.5s
    }

    .logo a:hover {
        letter-spacing: 3px;
    }

    .logo b {
        color: rgba(255, 0, 0, 0.874);
    }

    .info {
        width: 80%;
        margin: 10px auto 80px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .info p {
        color: rgba(255, 255, 255, 0.852);
        transition-duration: 1s;
    }

    .info p:hover {
        margin-left: 15px;
    }

    .contacts h1 {
        font-family: 'Trebuchet MS';
        color: rgba(255, 255, 255, 0.852);
    }

    .contacts b {
        color: gray;
    }

    .contacts a {
        color: gray;
        text-decoration: underline;
        text-underline-offset: 5px;
        transition-duration: 0.5s;
    }

    .contacts a:hover {
        font-size: 35px
    }

    .images img {
        border-radius: 50%;
        height: 30vh;
        border: 15px solid rgba(57, 57, 57, 0.516);
        transition-duration: 0.5s;
    }

    .images {
        display: flex;
        width: 70%;
        margin: auto;
    }

    #imgpos1 {
        position: relative;
        z-index: 1;
        transition-duration: 0.5s;
    }

    #imgpos1:hover {
        border-color: rgba(151, 0, 0, 0.902);
    }

    #imgpos2 {
        position: relative;
        z-index: 2;
        right: 50px;
        bottom: 40px;
        transition-duration: 0.5s;
    }

    #imgpos2:hover {
        border-color: rgba(255, 255, 255, 0.902);
    }

    #imgpos3 {
        position: relative;
        z-index: 3;
        right: 150px;
        top: 45px;
        transition-duration: 0.5s;
    }

    #imgpos3:hover {
        border-color: rgba(26, 77, 189, 0.902);
    }

    #imgpos4 {
        position: relative;
        z-index: 4;
        right: 250px;
        bottom: 40px;
        transition-duration: 0.5s;
    }

    #imgpos4:hover {
        border-color: rgba(232, 25, 25, 0.902);
    }

    #imgpos5 {
        position: relative;
        z-index: 5;
        right: 310px;
        transition-duration: 0.5s;
    }

    #imgpos5:hover {
        border-color: rgba(21, 19, 72, 0.902);
    }
</style>
<script>

</script>

</html>
