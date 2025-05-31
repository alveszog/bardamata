<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hamburgueria</title>
  <link href="https://fonts.googleapis.com/css2?family=Neka+Laurent&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Neka Laurent', cursive;
      background-color: #ffffff;
      color: #3e2f1c;
    }
    header {
      background-color: #6b3e26;
      color: #fff8f0;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
    }
    header img {
      width: 160px;
      margin-bottom: 10px;
    }
    nav {
      background-color: #4a2c1a;
      display: flex;
      justify-content: center;
      gap: 25px;
      padding: 14px 0;
    }
    nav a {
      color: #fff8f0;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #fdd49a;
    }
    .hero {
      background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0, 0, 0, 0.5)), url('https://files.oaiusercontent.com/file-ff2c5e8c-cc41-46a1-942f-00bcf4e3a1f4-image1.png');
      background-size: cover;
      background-position: center;
      height: 480px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff8f0;
      font-size: 3.2em;
      text-shadow: 4px 4px 8px rgba(0,0,0,0.7);
      padding: 0 20px;
      text-align: center;
    }
    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: 50px auto;
      background: #ffffff;
      box-shadow: 0 8px 16px rgba(0,0,0,0.05);
      border-radius: 16px;
    }
    h2 {
      font-size: 2.2em;
      color: #4a2c1a;
      border-left: 6px solid #e9b76c;
      padding-left: 20px;
      margin-bottom: 30px;
    }
    .menu-list h3 {
      margin-top: 40px;
      color: #6b3e26;
      font-size: 1.6em;
    }
    .menu-list p {
      margin: 10px 0;
      font-size: 1.2em;
    }
    .whatsapp-button {
      display: block;
      width: max-content;
      margin: 40px auto 0;
      padding: 16px 36px;
      font-size: 1.3em;
      color: white;
      background-color: #e9b76c;
      border: none;
      border-radius: 10px;
      text-decoration: none;
      font-family: 'Neka Laurent', cursive;
      transition: all 0.3s;
    }
    .whatsapp-button:hover {
      background-color: #d49f52;
      transform: translateY(-2px);
    }
    footer {
      background-color: #4a2c1a;
      color: #fff8f0;
      text-align: center;
      padding: 40px 20px;
      font-size: 1em;
      margin-top: 60px;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://files.oaiusercontent.com/file-ff2c5e8c-cc41-46a1-942f-00bcf4e3a1f4-image1.png" alt="Logo Hamburgueria">
    <h1>Bem-vindo</h1>
    <p>Sabor que vem da natureza</p>
  </header>
  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#menu">Cardápio</a>
    <a href="#contato">Contato</a>
  </nav>
  <div class="hero">
    Delícias Artesanais
  </div>
  <section id="sobre" class="section">
    <h2>Sobre Nós</h2>
    <p>Unimos o sabor irresistível dos hambúrgueres artesanais com ingredientes frescos e naturais. Nosso compromisso é oferecer qualidade, sabor e uma experiência única para os amantes de hambúrguer.</p>
  </section>
  <section id="menu" class="section">
    <h2>Cardápio</h2>
    <div class="menu-list">
      <h3>🍔 Hambúrgueres Especiais</h3>
      <p><strong>CLÁSSICO</strong> - R$18<br>Pão, Hambúrguer, Queijo, Alface, Tomate, Molho da Casa</p>
      <p><strong>X-BACON</strong> - R$20<br>Pão, Hambúrguer, Bacon, Presunto, Queijo, Ovo, Tomate, Molho Especial</p>
      <p><strong>X-ESPECIAL</strong> - R$28<br>Pão, 2 Hambúrgueres, 2 Bacon, 2 Cheddar, 2 Salsicha, 2 Ovos, Alface, Tomate</p>
      <p><strong>X-TUDÃO</strong> - R$24<br>Pão, Hambúrguer, Bacon, Presunto, Calabresa, Salsicha, Ovo, Mussarela, Alface, Tomate, Molho Especial</p>
      <p><strong>X-CALABRESA</strong> - R$22<br>Pão, Hambúrguer, Calabresa, Presunto, Ovo, Mussarela, Alface, Tomate, Molho Especial</p>

      <h3>🥤 Bebidas</h3>
      <p>Refrigerantes Lata - R$6</p>
      <p>Monster - R$13</p>
      <p>Gatorade (500ml) - R$8</p>
      <p>Red Bull (473ml) - R$21</p>

      <h3>🚚 Delivery</h3>
      <p>Taxa de Entrega: <strong>R$10</strong></p>
    </div>
    <a class="whatsapp-button" href="https://wa.me/5562994157872" target="_blank">Quero adquirir</a>
  </section>
  <section id="contato" class="section">
    <h2>Contato</h2>
    <p>Telefone para pedidos: <strong>(62) 99236-3958</strong></p>
  </section>
  <footer>
    <p>&copy; 2025 Hamburgueria. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
