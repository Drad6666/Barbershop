# Barbershop
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Барбершоп</title>

    <link rel="stylesheet" href="css/normalize.css">
    <link rel="stylesheet" href="style.css">
    <header class="main-header">
        <nav class="main-navigation">
            <li><a href="info.html"></a></li>
        </nav>
        <ul class="site-navigation">
            <li><a href="info-html">Информация</a></li>
            <li><a href="news-html">Новости</a></li>
            <li><a href="price-html">Пррайс-лист</a></li>
            <li><a href="catalog-html">Магазин</a></li>
            <li><a href="contacts-html">Контакты</a></li>

        </ul>

        <ul class="user-navigator">
            <li class="login-link">Вход</li>
        </ul>


    </header>
    <main class="container">
        <h1 class="visualy-hiden">Барбершоп "Бородинский"</h1>
        <section class="futeres">
            <h1 class="visualy-hiden">Преимущества</h1>
            <ul class="futeres-list">
                <li class="futers-item">
                    <h3>Круто</h3>
                    <p>Забудьте, как вы стриглись раньше. Мы сделаем из вас звезду футбола и кино</p>
                </li>
                <li class="futers-item">
                    <h3>Дорого</h3>
                    <p>Наши мастра - профессионалы своего дела и не могут стоить дешево</p>
                </li>
            </ul>
        </section>
        <section class="news">
            <h2>Новости</h2>
            <ul class="news-list">
                <li class="news-item">
                    <p>Нам наконец завезли Егермейстер! Теперь вы можете пропустить стаканчик во время стрижки</p>
                    <time datetime="2020.05.24">14 Мая</time>
                </li>
                <li class="news-item">
                    <p>В нашей команде пополнение Борис "Бритва"</p>
                    <time datetime="2020.05.24">18 Мая</time>
                </li>
            </ul>
            <a class="button" href="news.html">Все новости</a>

        </section>
        <section class="galery">
            <h2>Фотогалерея</h2>
            <figure class="galery-content">
                <a href="#"><img src="" alt="">
            </figure>
            <span class="button galery-button galery-button-back">Назад</span>
            <span class="button galery-button galery-button-next">Вперед</span>
        </section>

        <section class="contacts">
            <h2>Контактная Информация</h2>
            <p>
                Барбершоп "Бородинский" <br>
                адрес: г.Санкт-Петербург <br>
                Телефон: +30993232323<br>
            </p>
            <p>
                Время работы:
                пн-пт: с 10<br>
                сб-нд: c 12
            </p>
            <a class="button" href="map.html">Как проехать</a>
            <a class="button" href="contacts.html">Обратная связь</a>
        </section>
        <section class="appointment">
            <h2>Записаться</h2>
            <p class="appointment-info">Укажите удобную для вас дату записи</p>

        </section>
    </main>

    <footer class="main-footer">
        <p class="footer-contacts">
            Барбершоп "Бородинский"<br>
            адрес: г.Санкт-Петербург<br>
            <a href="map.html">Как нас найти?</a><br>
            Телефон: +30992323213
        </p>
        <div class="fotter-social">
            <b>Давайте дружить!</b>
            <ul>
                <li><a class="social-button" href="#">Вконтакте</a></li>
                <li><a class="social-button" href="#">Фейсбук</a></li>
                <li><a class="social-button" href="#">Инстаграмм</a></li>               
            </ul>
        </div>
        <p class="footer-copyright">
            <b>Разработано:</b>
            <a class="button" href="https://htmlacademy.ru">HTML Academy</a>
        </p>
    </footer>
    <section class="modal modal-login">
        <h2>Личный кабинет</h2>
        <p>Введите свой логин и пароль</p>
        <span class="modal-close">x</span>
    </section>
    <section class="modal modal-map">
        <h2 class="visualy-hiden">Как до нас добраться</h2>
        <p>Введите свой логин и пароль</p>
        <span class="modal-close">x</span>
    </section>
</head>

<body>

</body>

</html>
