<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Pessoal</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            color: #333;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1a1a2e;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #162447;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .portfolio, .blog, .store, .contact {
            margin-bottom: 40px;
        }
        footer {
            background-color: #1a1a2e;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        h1, h2 {
            color: #1a1a2e;
        }
        .product {
            border: 1px solid #ccc;
            padding: 15px;
            margin: 10px 0;
            display: flex;
            align-items: center;
        }
        .product img {
            max-width: 100px;
            height: auto;
            margin-right: 20px;
        }
        .product h3 {
            margin-top: 0;
        }
        .product p {
            margin-bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site Pessoal</h1>
    </header>
    <nav>
        <a href="#portfolio">Portfólio</a>
        <a href="#blog">Blog</a>
        <a href="#store">Loja</a>
        <a href="#contact">Contato</a>
    </nav>
    <div class="container">
        <section id="portfolio" class="portfolio">
            <h2>Portfólio</h2>
            <p>Esta é a seção de portfólio. Aqui você pode mostrar seus trabalhos anteriores.</p>
        </section>
        <section id="blog" class="blog">
            <h2>Blog</h2>
            <p>Esta é a seção de blog. Aqui você pode compartilhar seus pensamentos e ideias.</p>
        </section>
        <section id="store" class="store">
            <h2>Loja</h2>
            <div class="product">
                <img src="ebook1.jpg" alt="eBook 1">
                <div>
                    <h3>eBook 1</h3>
                    <p>Descrição do eBook 1</p>
                    <p>Preço: R$20,00</p>
                    <button>Adicionar ao Carrinho</button>
                </div>
            </div>
            <div class="product">
                <img src="ebook2.jpg" alt="eBook 2">
                <div>
                    <h3>eBook 2</h3>
                    <p>Descrição do eBook 2</p>
                    <p>Preço: R$30,00</p>
                    <button>Adicionar ao Carrinho</button>
                </div>
            </div>
        </section>
        <section id="contact" class="contact">
            <h2>Contato</h2>
            <form>
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                <label for="message">Mensagem:</label><br>
                <textarea id="message" name="message" rows="5" required></textarea><br><br>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Meu Site Pessoal</p>
    </footer>
</body>
</html>
