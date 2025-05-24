# Creche-Reborn
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Meu Site Pessoal</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fffafc;
      color: #333;
      line-height: 1.5;
    }

    header {
      background-color: #fbb6ce;
      color: #fff;
      text-align: center;
      padding: 2rem 1rem;
    }

    section {
      padding: 2rem 1rem;
      max-width: 800px;
      margin: 0 auto;
    }

    h2 {
      color: #e91e63;
    }

    .contato {
      background: #fde6ef;
      padding: 1.5rem;
      border-radius: 8px;
      margin-top: 2rem;
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
    }

    footer {
      background-color: #fbb6ce;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    /* RESPONSIVO */

    @media (max-width: 600px) {
      header {
        padding: 1.5rem 1rem;
      }

      section {
        padding: 1.5rem 1rem;
      }

      .contato {
        padding: 1rem;
        margin-top: 1.5rem;
      }

      h1 {
        font-size: 1.6rem;
      }

      h2 {
        font-size: 1.2rem;
      }

      p, li {
        font-size: 1rem;
      }

      ul, ol {
        padding-left: 1.2rem;
      }
    }

    @media (min-width: 601px) {
      h1 {
        font-size: 2.5rem;
      }

      h2 {
        font-size: 1.8rem;
      }

      p, li {
        font-size: 1.1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Bem-vindo ao Meu Site</h1>
    <p>Um espaço pessoal com muito carinho</p>
  </header>

  <section>
    <h2>Sobre Mim</h2>
    <p>Olá! Eu sou apaixonado(a) por tecnologia, design e comunicação. Criei este espaço para compartilhar ideias, projetos e dicas.</p>
  </section>

  <section>
    <h2>Meus Projetos</h2>
    <ul>
      <li>Projeto 1 - Site Responsivo</li>
      <li>Projeto 2 - Portfólio Interativo</li>
      <li>Projeto 3 - Blog Pessoal</li>
    </ul>
  </section>

  <section class="contato">
    <h2>Contato</h2>
    <p>Entre em contato comigo através do e-mail: <strong>seunome@email.com</strong></p>
  </section>

  <footer>
    <p>&copy; 2025 Meu Nome. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
