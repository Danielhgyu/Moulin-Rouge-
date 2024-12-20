<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Пропускной пункт</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(45deg, #ff6b81, #f1c40f);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: #fff;
        }
        .container {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 40px;
            border-radius: 12px;
            text-align: center;
            width: 90%;
            max-width: 400px;
        }
        h1 {
            font-size: 28px;
            margin-bottom: 20px;
        }
        p {
            font-size: 16px;
            margin-bottom: 20px;
        }
        input {
            padding: 12px;
            font-size: 18px;
            border: none;
            border-radius: 8px;
            width: 80%;
            margin-bottom: 20px;
            background-color: #f1f1f1;
            color: #333;
            text-align: center;
        }
        button {
            padding: 12px 24px;
            font-size: 18px;
            border: none;
            border-radius: 8px;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #45a049;
        }
        .error-message {
            color: #e74c3c;
            font-size: 14px;
            margin-top: 15px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Введите пароль для доступа</h1>
    <input type="password" id="password" placeholder="Введите пароль">
    <button onclick="checkPassword()">Войти</button>
    <div id="error-message" class="error-message" style="display: none;">Неверный пароль! Попробуйте снова.</div>
</div>

<script>
    function checkPassword() {
        const enteredPassword = document.getElementById("password").value.trim().toLowerCase();
        const errorMessage = document.getElementById("error-message");

        if (enteredPassword === "абсент") {
            window.location.href = "https://scanned.page/p/6764cca319f34";  // Переход на сайт
        } else {
            errorMessage.style.display = "block";  // Показываем ошибку
        }
    }
</script>

</body>
</html>

