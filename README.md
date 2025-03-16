# -GTA5RP
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GTA5RP Вирты</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #111; color: white; text-align: center; }
        .container { max-width: 500px; margin: 50px auto; padding: 20px; background: #222; border-radius: 10px; }
        select, input, button { width: 100%; padding: 10px; margin: 10px 0; border: none; border-radius: 5px; }
        button { background: #28a745; color: white; cursor: pointer; }
        button:hover { background: #218838; }
    </style>
    <script>
        function changeLanguage() {
            var lang = document.getElementById("language").value;
            document.getElementById("title").innerText = lang === "en" ? "GTA5RP Virtual Currency Shop" : "Магазин виртов GTA5RP";
            document.getElementById("priceLabel").innerText = lang === "en" ? "Price: $10 per 1M" : "Цена: $10 за 1М";
            document.getElementById("buyButton").innerText = lang === "en" ? "Buy Now" : "Купить";
        }
    </script>
</head>
<body>
    <div class="container">
        <h1 id="title">Магазин виртов GTA5RP</h1>
        <label for="language">Выберите язык:</label>
        <select id="language" onchange="changeLanguage()">
            <option value="ru">Русский</option>
            <option value="en">English</option>
        </select>
        <p id="priceLabel">Цена: $10 за 1М</p>
        <input type="text" placeholder="Введите ваш ник" id="username">
        <button id="buyButton">Купить</button>
    </div>
</body>
</html>
