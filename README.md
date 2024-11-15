# Be-Better-than-ever-website
Modedesign shop
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be Better - Elegance Redefined</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
        }
        header {
            background-color: #000;
            padding: 20px;
            text-align: center;
            position: relative;
        }
        header img {
            width: 100px;
            height: auto;
        }
        header h1 {
            font-size: 2.5rem;
            color: #e53935;
            margin: 10px 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #222;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
        }
        nav a:hover {
            color: #e53935;
        }
        .hero {
            text-align: center;
            padding: 100px 20px;
            background-image: url('https://via.placeholder.com/1500x600/000000/e53935?text=Entdecke+die+Kollektion');
            background-size: cover;
            background-position: center;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .product {
            background-color: #111;
            margin: 10px;
            padding: 15px;
            border: 1px solid #e53935;
            border-radius: 5px;
            width: 300px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            border-bottom: 1px solid #e53935;
            margin-bottom: 10px;
        }
        .product h3 {
            font-size: 1.5rem;
            margin: 10px 0;
        }
        .product p {
            font-size: 1rem;
            margin-bottom: 10px;
        }
        .product button {
            background-color: #e53935;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 1rem;
        }
        .product button:hover {
            background-color: #c62828;
        }
        footer {
            background-color: #111;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/Red_Rose.JPG/640px-Red_Rose.JPG" alt="Be Better Logo - Rote Rose">
        <h1>Be Better</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Produkte</a>
        <a href="#about">Über Uns</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <div class="hero" id="home">
        <h2>Stilvolle Mode für Anspruchsvolle</h2>
        <p>Entdecke die Kollektion von Be Better und hebe deinen Stil auf ein neues Level.</p>
    </div>
    <section class="products" id="products">
        <div class="product">
            <img src="https://via.placeholder.com/300x300/000000/e53935?text=Luxuriös" alt="Produkt 1">
            <h3>Luxuriöse Kleidung</h3>
            <p>Eleganz, die für sich spricht.</p>
            <button>Kaufen</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300x300/000000/e53935?text=Modern" alt="Produkt 2">
            <h3>Moderner Stil</h3>
            <p>Perfekt für jede Gelegenheit.</p>
            <button>Kaufen</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300x300/000000/e53935?text=Exklusiv" alt="Produkt 3">
            <h3>Exklusive Designs</h3>
            <p>Mode, die inspiriert.</p>
            <button>Kaufen</button>
        </div>
    </section>
    <footer>
        <p>© 2024 Be Better. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
