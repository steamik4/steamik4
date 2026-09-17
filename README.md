<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Bio</title>
    <!-- Подключение шрифтов и стилей (можно добавить свои стили в tag <style> или отдельный файл style.css) -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="wrapper">
        <!-- Шапка -->
        <header>
            <h1>MY PROFILE BIO</h1>
        </header>

        <main>
            <!-- Блок с карточками-ссылками -->
            <section class="links-section">
                
                <!-- Ссылка 1 -->
                <a href="https://t.me/your_username" class="card">
                    <div class="card-text">
                        <h3>Telegram</h3>
                        <p>Основной аккаунт для связи</p>
                    </div>
                    <div class="card-icon">
                        <img src="img/telegram.png" alt="Telegram">
                    </div>
                </a>

                <!-- Ссылка 2 -->
                <a href="https://funpay.com/users/your_id" class="card">
                    <div class="card-text">
                        <h3>FunPay</h3>
                        <p>Мои товары и услуги</p>
                    </div>
                    <div class="card-icon">
                        <img src="img/funpay.png" alt="FunPay">
                    </div>
                </a>

            </section>

            <!-- Блок с дополнительной информацией (например, отзывы/рейтинг) -->
            <section class="info-section">
                <div class="rating-box">
                    <span>Рейтинг<br>продавца<br>5.0 из 5</span>
                    <div><span>100 отзывов</span></div>
                </div>
                
                <a href="https://t.me/your_shop" class="shop-card">
                    <h3>Крупные<br>заказы</h3>
                    <span>КЛИКАТЬ ТУТ</span>
                </a>
            </section>

            <!-- Блок с картинками-отзывами -->
            <section class="reviews-section">
                <div class="review-img">
                    <img src="img/otzyv1.png" alt="Отзыв 1">
                </div>
                <div class="review-img">
                    <img src="img/otzyv2.png" alt="Отзыв 2">
                </div>
            </section>
        </main>
    </div>

</body>
</html>
