# interior.github.io
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Фрилансер Дизайнер</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Навигация -->
    <header>
        <nav>
            <ul>
                <li><a href="#about">Обо мне</a></li>
                <li><a href="#portfolio">Портфолио</a></li>
                <li><a href="#services">Услуги</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <!-- Раздел "Обо мне" -->
    <section id="about">
        <h1>Привет! Я - [Ваше имя]</h1>
        <p>Я фрилансер-дизайнер с опытом в создании уникальных и креативных решений для вашего бизнеса.</p>
    </section>

    <!-- Раздел Портфолио -->
    <section id="portfolio">
        <h2>Моё Портфолио</h2>
        <div class="gallery">
            <!-- Добавьте изображения ваших работ -->
            <img src="work1.jpg" alt="Работа 1">
            <img src="work2.jpg" alt="Работа 2">
            <img src="work3.jpg" alt="Работа 3">
        </div>
    </section>

    <!-- Раздел Услуги -->
    <section id="services">
        <h2>Услуги</h2>
        <ul>
            <li>Веб-дизайн</li>
            <li>Графический дизайн</li>
            <li>Логотипы и фирменный стиль</li>
            <li>UX/UI дизайн</li>
        </ul>
    </section>

    <!-- Раздел Контакты -->
    <section id="contact">
        <h2>Контакты</h2>
        <p>Если вы хотите обсудить проект или задать вопрос, свяжитесь со мной!</p>
        <form id="contactForm">
            <label for="name">Имя:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Сообщение:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Отправить</button>
        </form>
    </section>

    <footer>
        <p>© 2025. Все права защищены.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* Сброс стилей */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Основной стиль */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Навигация */
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Разделы */
section {
    padding: 40px;
    margin: 20px 0;
}

h1, h2 {
    margin-bottom: 20px;
}

#portfolio .gallery {
    display: flex;
    justify-content: space-between;
}

#portfolio .gallery img {
    width: 30%;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Формы */
form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-bottom: 10px;
    font-weight: bold;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

form button {
    padding: 10px 20px;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}

/* Футер */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
/* Сброс стилей */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Основной стиль */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Навигация */
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Разделы */
section {
    padding: 40px;
    margin: 20px 0;
}

h1, h2 {
    margin-bottom: 20px;
}

#portfolio .gallery {
    display: flex;
    justify-content: space-between;
}

#portfolio .gallery img {
    width: 30%;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Формы */
form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-bottom: 10px;
    font-weight: bold;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

form button {
    padding: 10px 20px;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}

/* Футер */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    /* Сброс стилей */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Основной стиль */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Навигация */
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Разделы */
section {
    padding: 40px;
    margin: 20px 0;
}

h1, h2 {
    margin-bottom: 20px;
}

#portfolio .gallery {
    display: flex;
    justify-content: space-between;
}

#portfolio .gallery img {
    width: 30%;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Формы */
form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-bottom: 10px;
    font-weight: bold;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

form button {
    padding: 10px 20px;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}

/* Футер */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
document.getElementById('contactForm').addEventListener('submit', function(e) {
    e.preventDefault();

    let name = document.getElementById('name').value;
    let email = document.getElementById('email').value;
    let message = document.getElementById('message').value;

    if (name && email && message) {
        alert('Сообщение отправлено!');
        this.reset(); // Очистить форму
    } else {
        alert('Пожалуйста, заполните все поля!');
    }
});
