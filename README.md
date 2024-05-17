<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fajny Kubek</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: linear-gradient(to right, orange, yellow);
            padding: 10px 0;
            text-align: center;
            color: white;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #fff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav a {
            padding: 15px 20px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #f0f0f0;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            background: #fff;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            flex: 1 1 calc(33.333% - 40px);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
            padding-bottom: 10px;
            margin-bottom: 10px;
        }
        .product h3 {
            margin: 0 0 10px 0;
        }
        .product p {
            margin: 0 0 10px 0;
        }
        .product button {
            background: linear-gradient(to right, orange, yellow);
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        .product button:hover {
            background: linear-gradient(to right, darkorange, gold);
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Fajny Kubek</h1>
        <p>Twój unikalny kubek, który podkreśla twoją osobowość i dodaje uroku ulubionym chwilom.</p>
    </header>
    <nav>
        <a href="#dla-niej">Dla Niej</a>
        <a href="#dla-niego">Dla Niego</a>
        <a href="#dla-dziecka">Dla Dziecka</a>
        <a href="#zabawne">Zabawne</a>
        <a href="#na-okazje">Na Okazje</a>
        <a href="#zawody">Zawody</a>
    </nav>
    <div class="container">
        <div id="dla-niej" class="section">
            <h2>Dla Niej</h2>
            <div class="products">
                <div class="product">
                    <img src="kubek1.jpg" alt="Kubek dla Niej 1">
                    <h3>Kubek dla Niej 1</h3>
                    <p>Opis kubka dla Niej 1</p>
                    <button>Zamów</button>
                </div>
                <div class="product">
                    <img src="kubek2.jpg" alt="Kubek dla Niej 2">
                    <h3>Kubek dla Niej 2</h3>
                    <p>Opis kubka dla Niej 2</p>
                    <button>Zamów</button>
                </div>
                <!-- Dodaj więcej produktów tutaj -->
            </div>
        </div>
        <div id="dla-niego" class="section">
            <h2>Dla Niego</h2>
            <div class="products">
                <div class="product">
                    <img src="kubek3.jpg" alt="Kubek dla Niego 1">
                    <h3>Kubek dla Niego 1</h3>
                    <p>Opis kubka dla Niego 1</p>
                    <button>Zamów</button>
                </div>
                <div class="product">
                    <img src="kubek4.jpg" alt="Kubek dla Niego 2">
                    <h3>Kubek dla Niego 2</h3>
                    <p>Opis kubka dla Niego 2</p>
                    <button>Zamów</button>
                </div>
                <!-- Dodaj więcej produktów tutaj -->
            </div>
        </div>
        <div id="dla-dziecka" class="section">
            <h2>Dla Dziecka</h2>
            <div class="products">
                <div class="product">
                    <img src="kubek5.jpg" alt="Kubek dla Dziecka 1">
                    <h3>Kubek dla Dziecka 1</h3>
                    <p>Opis kubka dla Dziecka 1</p>
                    <button>Zamów</button>
                </div>
                <div class="product">
                    <img src="kubek6.jpg" alt="Kubek dla Dziecka 2">
                    <h3>Kubek dla Dziecka 2</h3>
                    <p>Opis kubka dla Dziecka 2</p>
                    <button>Zamów</button>
                </div>
                <!-- Dodaj więcej produktów tutaj -->
            </div>
        </div>
        <div id="zabawne" class="section">
            <h2>Zabawne</h2>
            <div class="products">
                <div class="product">
                    <img src="kubek7.jpg" alt="Kubek Zabawny 1">
                    <h3>Kubek Zabawny 1</h3
