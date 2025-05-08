# Site-de-vendas-
Hambúrgueres 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Willian Costa - Hambúrguer, Pizza & Conhecimento</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background: url('https://images.unsplash.com/photo-1606755962773-5129cfdabf74') no-repeat center center/cover;
      color: white;
      padding: 6rem 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      background: rgba(0,0,0,0.6);
      display: inline-block;
      padding: 1rem 2rem;
      border-radius: 10px;
    }

    nav {
      background-color: #111;
      padding: 1rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: auto;
    }

    .box {
      background: white;
      margin-bottom: 2rem;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }

    h2 {
      color: #c62828;
    }

    .btn {
      display: inline-block;
      background: #c62828;
      color: white;
      padding: 0.8rem 1.5rem;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 1rem;
    }

    .galeria {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .galeria img {
      width: 100%;
      max-width: 300px;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }

    .video {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .video iframe {
      position: absolute;
      width: 100%;
      height: 100%;
      left: 0;
      top: 0;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        gap: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Willian Costa</h1>
    <p style="background:rgba(0,0,0,0.6);padding:0.5rem;border-radius:5px;">Hambúrguer, Pizza & Conhecimento com Sabor</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#galeria">Galeria</a>
    <a href="#videos">Vídeos</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="sobre" class="box">
    <h2>Quem Sou</h2>
    <p>Sou Willian, apaixonado por gastronomia e especialista em hambúrgueres artesanais e pizzas. Com mais de 9 anos de experiência em restaurantes e delivery, transformei minha paixão em negócio — e agora, quero compartilhar tudo o que aprendi com você.</p>
  </section>

  <section id="servicos" class="box">
    <h2>O que Eu Faço</h2>
    <ul>
      <li>Venda online de hambúrgueres e pizzas de qualidade</li>
      <li>Consultoria para abrir seu próprio negócio</li>
      <li>Mentorias práticas para iniciantes no ramo</li>
      <li>Criação de cardápio e treinamento de equipe</li>
    </ul>
    <a href="#contato" class="btn">Fale Comigo</a>
  </section>

  <section id="galeria" class="box">
    <h2>Galeria de Sabores</h2>
    <div class="galeria">
      <img src="https://images.unsplash.com/photo-1550547660-d9450f859349" alt="Hambúrguer Artesanal">
      <img src="https://images.unsplash.com/photo-1601924928142-3ccde40fa66f" alt="Pizza Artesanal">
      <img src="https://images.unsplash.com/photo-1586190848861-99aa4a171e90" alt="Cozinha Profissional">
    </div>
  </section>

  <section id="videos" class="box">
    <h2>Assista e Aprenda</h2>
    <p>Veja na prática como eu preparo hambúrgueres e pizzas de qualidade, com dicas exclusivas para você aplicar no seu negócio.</p>
    <div class="video">
      <iframe src="https://www.youtube.com/embed/q2H6G6SbUo8" frameborder="0" allowfullscreen></iframe>
    </div>
  </section>

  <section id="contato" class="box">
    <h2>Entre em Contato</h2>
    <p>Quer aprender comigo ou fazer um pedido especial? Me chame!</p>
    <p>Email: <a href="mailto:contato@willianburgerpizza.com">contato@willianburgerpizza.com</a></p>
    <p>Instagram: <a href="https://www.instagram.com/relicariogastronomia" target="_blank">@relicariogastronomia</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Willian Costa. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
