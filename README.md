<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Fitness - Graziele Pollo Galindo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #fff;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .product {
            background-color: #fff;
            margin: 15px;
            padding: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            flex-basis: calc(33.333% - 30px);
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .product h2 {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .product p {
            font-size: 1em;
            margin: 10px 0;
            color: #555;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            transition: transform 0.3s;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        footer a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
            font-size: 1.2em;
        }
    </style>
</head>
<body>

    <header>
        <h1>Graziele Pollo Galindo - Moda Fitness</h1>
    </header>

    <div class="container">
        <section class="products">
            <div class="product">
                <img src="produto1.jpg" alt="Produto 1">
                <h2>Top Fitness</h2>
                <p>R$ 79,90</p>
            </div>
            <div class="product">
                <img src="produto2.jpg" alt="Produto 2">
                <h2>Legging de Compressão</h2>
                <p>R$ 99,90</p>
            </div>
            <div class="product">
                <img src="produto3.jpg" alt="Produto 3">
                <h2>Camiseta Dry Fit</h2>
                <p>R$ 59,90</p>
            </div>
        </section>

        <h2>Galeria de Fotos</h2>
        <section class="gallery">
            <img src="foto1.jpg" alt="Foto 1">
            <img src="foto2.jpg" alt="Foto 2">
            <img src="foto3.jpg" alt="Foto 3">
        </section>
    </div>

    <footer>
        <p>Conecte-se comigo nas redes sociais</p>
        <a href="https://www.instagram.com/seu_perfil" target="_blank">Instagram</a>
        <a href="https://wa.me/seu_numero_whatsapp" target="_blank">WhatsApp</a>
    </footer>

</body>
</html>
