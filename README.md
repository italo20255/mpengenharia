<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MP Engenharia - Marcos Peres Junior</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background: #fff;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #000;
      color: gold;
      padding: 20px;
      text-align: center;
    }
    /* O título da landing page e o nome do engenheiro em Verdana */
    header h1 {
      font-family: Verdana, sans-serif;
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2em;
    }
    .logo {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 20px;
    }
    .logo img {
      max-width: 100px;
      border: 2px solid gold;
      border-radius: 50%;
    }
    .logo-text {
      font-family: Verdana, sans-serif;
      font-size: 2em;
      color: gold;
      margin-left: 10px;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: 20px auto;
      padding: 20px;
    }
    .description {
      text-align: center;
      margin: 40px 0;
    }
    .description h2 {
      font-size: 2em;
      margin-bottom: 20px;
    }
    .description p {
      font-size: 1.1em;
      color: #555;
      margin-bottom: 20px;
    }
    .cta {
      display: inline-block;
      padding: 15px 30px;
      background: gold;
      color: #000;
      text-decoration: none;
      font-size: 1.2em;
      border-radius: 5px;
    }
    /* Formulário de contato */
    #contato {
      margin-top: 40px;
    }
    #contato h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    form {
      max-width: 600px;
      margin: 0 auto;
    }
    form div {
      margin-bottom: 15px;
    }
    form label {
      display: block;
      margin-bottom: 5px;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      background: #000;
      color: gold;
      border: none;
      padding: 10px 20px;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1em;
    }
    footer {
      background: #000;
      color: gold;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <!-- Logo em preto e dourado -->
      <img src="https://via.placeholder.com/100x100/000000/FFD700?text=MP" alt="Logo MP Engenharia">
      <div class="logo-text">MP Engenharia</div>
    </div>
    <h1>Marcos Peres Junior</h1>
    <p>Transformando projetos em realidade com excelência e inovação</p>
  </header>

  <div class="container">
    <section class="description">
      <h2>Soluções Completas para o Seu Imóvel</h2>
      <p>
        Na MP Engenharia, oferecemos serviços especializados em regularização de imóveis, emissão de habite-se, documentação para o programa Minha Casa Minha Vida e projetos comerciais e residenciais. Nossa equipe unifica expertise e tecnologia para proporcionar agilidade, segurança e qualidade em cada etapa do seu projeto.
      </p>
      <a href="#contato" class="cta">Entre em Contato</a>
    </section>

    <section id="contato">
      <h2>Contato</h2>
      <form id="contatoForm" action="#" method="POST">
        <div>
          <label for="nome">Nome:</label>
          <input type="text" id="nome" name="nome" required>
        </div>
        <div>
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" required>
        </div>
        <div>
          <label for="mensagem">Mensagem:</label>
          <textarea id="mensagem" name="mensagem" rows="5" required></textarea>
        </div>
        <div>
          <button type="submit">Enviar</button>
        </div>
      </form>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 MP Engenharia. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
