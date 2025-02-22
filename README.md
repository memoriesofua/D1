<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Оцифрування спогадів</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #4a90e2;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
        }
        .services, .contact {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .services h2, .contact h2 {
            margin-bottom: 15px;
        }
        footer {
            text-align: center;
            padding: 15px 0;
            background-color: #333;
            color: white;
        }
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
            }
            nav a {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Послуги з оцифрування спогадів</h1>
        <p>Збережіть пам'ять про близьких назавжди</p>
    </header>

    <nav>
        <a href="#services">Послуги</a>
        <a href="#contact">Контакти</a>
    </nav>

    <div class="container">
        <section id="services" class="services">
            <h2>Наші послуги</h2>
            <ul>
                <li>Оцифрування фото та відеоархівів</li>
                <li>Запис аудіоспогадів родичів та друзів</li>
                <li>Створення пам'ятних відеороликів</li>
                <li>Обробка та відновлення старих фотографій</li>
            </ul>
        </section>

        <section id="contact" class="contact">
            <h2>Зв'яжіться з нами</h2>
            <form>
                <label for="name">Ім'я:</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">Електронна пошта:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">Повідомлення:</label><br>
                <textarea id="message" name="message" rows="5" required></textarea><br><br>

                <button type="submit">Надіслати</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Оцифрування спогадів. Всі права захищені.</p>
    </footer>
</body>
</html>
