<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Creche Reborn: carinho e cuidado para seus bebês reborn. Oferecemos banho, roupinhas sob medida e ensaios fotográficos.">
  <title>Creche Reborn</title>
  <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Reset e configurações iniciais */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Nunito', sans-serif;
      background-color: #fffafc;
      color: #333;
      line-height: 1.6;
    }

    /* Cabeçalho */
    header {
      background: linear-gradient(135deg, #fbb6ce, #e91e63);
      color: white;
      text-align: center;
      padding: 3rem 1rem;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1.2rem;
    }

    /* Navegação */
    nav {
      background-color: #fde6ef;
      text-align: center;
      padding: 1rem 0;
    }
    nav a {
      color: #e91e63;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #c2185b;
    }

    /* Conteúdo principal */
    main {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: 0 auto;
    }
    h2 {
      color: #e91e63;
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    ul {
      list-style: none;
      padding-left: 1.5rem;
    }
    li {
      margin-bottom: 0.5rem;
    }

    /* Seção de contato */
    .contato {
      background: #fde6ef;
      padding: 2rem;
      border-radius: 8px;
      text-align: center;
      margin-top: 2rem;
    }
    .whatsapp-btn {
      display: inline-block;
      background-color: #25d366;
      color: white;
      padding: 1rem 1.5rem;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1rem;
      transition: background 0.3s;
    }
    .whatsapp-btn:hover {
      background-color: #128c7e;
    }

    /* Rodapé */
    footer {
      background-color: #fbb6ce;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    /* Responsividade */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2.5rem;
      }
      header p {
        font-size: 1rem;
      }
      h2 {
        font-size: 1.6rem;
      }
      nav a {
        display: block;
        margin: 0.5rem 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Creche Reborn</h1>
    <p>Um lugar de carinho e cuidado para os seus bebês reborn</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
  </nav>

  <main>
    <section id="sobre">
      <h2>Sobre Nós</h2>
      <p>Somos apaixonados por bonecas reborn e criamos um espaço onde elas recebem o cuidado que merecem.</p>
    </section>

    <section id="servicos">
      <h2>Serviços</h2>
      <ul>
        <li>Banho e cuidados especiais</li>
        <li>Roupinhas sob medida</li>
        <li>Ensaio fotográfico profissional</li>
      </ul>
    </section>

    <section id="contato" class="contato">
      <h2>Contato</h2>
      <p>Fale com a gente pelo WhatsApp:</p>
      <a class="whatsapp-btn" href="https://wa.me/5511987846694" target="_blank" rel="noopener" aria-label="Conversar conosco no WhatsApp">
        📲 Conversar no WhatsApp
      </a>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Creche Reborn. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
