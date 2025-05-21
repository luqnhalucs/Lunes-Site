<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lunes' Designs - Lucas Nunes Godoy</title>
  <style>
    :root {
      --marrom: #9c6746;
      --marrom-escuro: #5c3a29;
      --bege: #f5e9dc;
    }
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Arial', sans-serif;
      background-color: var(--bege);
      color: var(--marrom-escuro);
      scroll-behavior: smooth;
    }
    header {
      background: var(--marrom);
      color: white;
      padding: 30px 20px;
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }
    header h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: var(--bege);
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      opacity: 0;
      transform: translateY(50px);
      animation: slideUp 1s forwards;
    }
    section:nth-of-type(2) { animation-delay: 0.3s; }
    section:nth-of-type(3) { animation-delay: 0.6s; }
    section:nth-of-type(4) { animation-delay: 0.9s; }
    h2 {
      font-size: 2em;
      margin-bottom: 20px;
      color: var(--marrom);
    }
    .portfolio img {
      width: 100%;
      max-width: 300px;
      margin: 10px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      transition: transform 0.3s ease;
    }
    .portfolio img:hover {
      transform: scale(1.05);
    }
    ul {
      list-style: none;
      margin-top: 20px;
    }
    ul li {
      margin-bottom: 10px;
      font-size: 1.1em;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 12px;
      margin-top: 10px;
      border: 2px solid var(--marrom);
      border-radius: 5px;
      background: #fff;
    }
    .contact-form button, .download-button {
      margin-top: 10px;
      padding: 12px 20px;
      background-color: var(--marrom);
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      transition: background 0.3s ease;
    }
    .contact-form button:hover, .download-button:hover {
      background-color: var(--marrom-escuro);
    }
    footer {
      background-color: var(--marrom);
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    .social a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    .social a:hover {
      color: var(--bege);
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.95); }
      to { opacity: 1; transform: scale(1); }
    }
    @keyframes slideUp {
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

<header>
  <h1>Lunes' Designs</h1>
  <p>Design Gráfico Profissional por Lucas Nunes Godoy</p>
  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#portfolio">Portfólio</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<section id="sobre">
  <h2>Sobre Mim</h2>
  <p>Sou Lucas Nunes Godoy, designer gráfico, apaixonado por transformar ideias em identidade visual marcante. Com soluções criativas e personalizadas, ajudo você a se destacar no mundo digital e impresso.</p>
</section>

<section id="portfolio">
  <h2>Portfólio</h2>
  <div class="portfolio">
    <img src="logo.png" alt="Logo Lunes' Designs">
    <img src="tabela-precos.png" alt="Tabela de Preços">
    <img src="trabalho1.png" alt="Arte exemplo">
  </div>
  <p>* Substitua ou adicione mais imagens conforme seu portfólio.</p>
</section>

<section id="servicos">
  <h2>Serviços</h2>
  <ul>
    <li>Arte Avulsa - R$ 18</li>
    <li>Kit com 3 artes - R$ 50</li>
    <li>Kit com 5 artes - R$ 75</li>
    <li>Stories Animados - R$ 25</li>
    <li>Criação de Logotipo - R$ 120</li>
    <li>Manual de Marca - R$ 150</li>
    <li>Cartão de Visita Digital - R$ 35</li>
    <li>Paleta de Cores + Tipografia - R$ 50</li>
    <li>Cartão de Visita (Impresso) - R$ 40</li>
    <li>Flyer Digital - R$ 30</li>
    <li>Panfleto A5 (Impresso) - R$ 25</li>
    <li>Tag de Produto - R$ 20</li>
    <li>Rótulo de Embalagem - R$ 35</li>
  </ul>

  <a class="download-button" href="tabela-de-precos.pdf" download>Baixar Tabela de Preços (PDF)</a>
</section>

<section id="contato">
  <h2>Contato</h2>
  <p>Telefone: <a href="tel:+5517981624813">(17) 98162-4813</a></p>
  <p>E-mail: <a href="mailto:luqnhalucs@gmail.com">luqnhalucs@gmail.com</a></p>
  <p>Instagram: <a href="https://www.instagram.com/lunes_designs" target="_blank">@lunes_designs</a></p>

  <form class="contact-form">
    <input type="text" placeholder="Seu nome" required>
    <input type="email" placeholder="Seu e-mail" required>
    <textarea placeholder="Sua mensagem" rows="5" required></textarea>
    <button type="submit">Enviar</button>
  </form>
</section>

<footer>
  <p>© 2025 Lucas Nunes Godoy - Lunes' Designs. Todos os direitos reservados.</p>
  <div class="social">
    <a href="https://www.instagram.com/lunes_designs" target="_blank">Instagram</a> |
    <a href="mailto:luqnhalucs@gmail.com">E-mail</a> |
    <a href="tel:+5517981624813">WhatsApp</a>
  </div>
</footer>

</body>
</html>
