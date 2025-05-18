<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Galaxy Shop - Contas Blox Fruits</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0d0f1b;
      color: #fff;
    }
    header {
      background-color: #13152a;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-weight: bold;
      font-size: 1.5rem;
      color: #00f0ff;
    }
    .menu a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
    }
    .banner {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 20px;
    }
    .banner img {
      width: 200px;
      border-radius: 10px;
      border: 2px solid #00f0ff;
    }
    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background-color: #1a1d35;
      border-radius: 10px;
      padding: 15px;
      border: 2px solid #00f0ff;
      text-align: center;
    }
    .card img {
      width: 100%;
      border-radius: 8px;
    }
    .preco {
      color: #0f0;
      font-weight: bold;
      margin: 10px 0;
    }
    .btn {
      background-color: #00f0ff;
      color: #000;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }
    .btn:hover {
      background-color: #00c4d4;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Galaxy Shop</div>
    <div class="menu">
      <a href="#">Início</a>
      <a href="#">Produtos</a>
      <a href="#">Carrinho</a>
      <a href="#">Entrar</a>
    </div>
  </header>  <section class="banner">
    <img src="https://via.placeholder.com/200x250?text=Godhuman" alt="Contas com Godhuman">
    <img src="https://via.placeholder.com/200x250?text=Frutas+F%C3%ADsicas" alt="Frutas Físicas via Trade">
  </section>  <section class="produtos">
    <div class="card">
      <img src="https://via.placeholder.com/250x150?text=Level+Max+Godhuman" alt="Produto">
      <h3>Godhuman LVL MAX</h3>
      <div class="preco">R$ 10,00 no Pix</div>
      <button class="btn">Comprar Agora</button>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/250x150?text=Godhuman+Soul+Guitar" alt="Produto">
      <h3>Godhuman + Soul Guitar</h3>
      <div class="preco">R$ 13,00 no Pix</div>
      <button class="btn">Comprar Agora</button>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/250x150?text=CDK+%2B+SG" alt="Produto">
      <h3>Godhuman + CDK + SG</h3>
      <div class="preco">R$ 13,00 no Pix</div>
      <button class="btn">Comprar Agora</button>
    </div>
  </section>
</body>
</html>