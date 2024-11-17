<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Cosméticos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Loja de Cosméticos</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre Nós</a></li>
                <li><a href="#produtos">Produtos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Bem-vindo à nossa loja!</h2>
        <p>Descubra os melhores produtos para realçar sua beleza.</p>
        <button>Compre Agora</button>
    </section>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Somos apaixonados por beleza e qualidade. Conheça nossa história!</p>
    </section>

    <section id="produtos">
        <h2>Nossos Produtos</h2>
        <div class="produto">
            <img src="produto1.jpg" alt="Produto 1">
            <h3>Produto 1</h3>
            <p>R$ 49,90</p>
            <button>Comprar</button>
        </div>
        <div class="produto">
            <img src="produto2.jpg" alt="Produto 2">
            <h3>Produto 2</h3>
            <p>R$ 29,90</p>
            <button>Comprar</button>
        </div>
    </section>

    <section id="contato">
        <h2>Fale Conosco</h2>
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>© 2024 Loja de Cosméticos. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f4a1d1;
    padding: 20px;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 10px;
}

header nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

section {
    padding: 20px;
    text-align: center;
}

section#produtos .produto {
    display: inline-block;
    margin: 10px;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}

