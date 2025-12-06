# Code Citations

## License: unknown
https://github.com/shvet12sov/random/tree/0a9f60739c56d8871be52dafb8be66590ca8235d/index.html

````markdown
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Генератор случайных чисел</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        .container {
            margin-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
        }
        button:hover {
            background-color: #0056b3;
        }
        .result {
            margin-top: 20px;
            font-size: 24px;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Генератор случайных чисел</h1>
        <p>Нажмите кнопку, чтобы сгенерировать случайное число от 1 до 100:</p>
        <button onclick="generateRandomNumber()">Сгенерировать</button>
        <div class="result" id="result">Ваше число появится здесь</div>
    </div>

    <script>
        function generateRandomNumber() {
            const randomNumber = Math.floor(Math.random() * 100) + 1;
            document.getElementById('result').textContent = `Случайное число: ${randomNumber}`;
        }
    </script>
</body>
</html>
````

