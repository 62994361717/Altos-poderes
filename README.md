# Altos-poderes
https://github.com/ricocria7/altos-poderes
index.html:<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>⚜️ Altos Poderes</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0b0b0b;
      color: #fff;
    }
    header {
      background: #111;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: gold;
    }
    nav {
      background: #1a1a1a;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #f1f1f1;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 40px 20px;
    }
    .hero video {
      width: 90%;
      max-width: 800px;
      border: 2px solid gold;
      border-radius: 10px;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section h2 {
      color: gold;
      margin-bottom: 10px;
    }
    .products, .testimonials {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
    }
    .product, .testimonial {
      background: #1c1c1c;
      padding: 20px;
      border-radius: 10px;
      border: 1px solid #333;
    }
    footer {
      background: #111;
      padding: 20px;
      text-align: center;
      font-size: 0.9em;
    }
    .contact a {
      color: gold;
      text-decoration: none;
    }
  </style>
</head>
<body>

<header>
  <h1>⚜️ Altos Poderes</h1>
</header>

<nav>
  <a href="#produtos">Produtos</a>
  <a href="#videos">Vídeos</a>
  <a href="#contato">Contato</a>
</nav>

<section class="hero" id="videos">
  <h2>Vídeo Principal</h2>
  <video controls>
    <source src="video.mp4" type="video/mp4" />
    Seu navegador não suporta vídeo.
  </video>
</section>

<section class="section" id="produtos">
  <h2>Produtos em Destaque</h2>
  <div class="products">
    <div class="product">
      <h3>Produto 1</h3>
      <p>Descrição do produto. Preço: R$ 49,90</p>
    </div>
    <div class="product">
      <h3>Produto 2</h3>
      <p>Descrição do produto. Preço: R$ 89,90</p>
    </div>
  </div>
</section>

<section class="section">
  <h2>Depoimentos</h2>
  <div class="testimonials">
    <div class="testimonial">
      <p>“Site brabo demais! Produtos de qualidade.”</p>
      <strong>— Cliente Satisfeito</strong>
    </div>
    <div class="testimonial">
      <p>“Entrega rápida e atendimento nota 10.”</p>
      <strong>— Cliente Fiel</strong>
    </div>
  </div>
</section>

<section class="section contact" id="contato">
  <h2>Contato</h2>
  <p>📞 WhatsApp: <a href="https://wa.me/5562994361717" target="_blank">62 99436-1717</a></p>
  <p>📸 Instagram: <a href="https://instagram.com/mcilanzinho06" target="_blank">@mcilanzinho06</a></p>
</section>

<footer>
  <p>&copy; 2025 ⚜️ Altos Poderes - Todos os direitos reservados.</p>
</footer>

</body>
</html>
