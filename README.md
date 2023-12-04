<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Littlepeterzin - Página Pessoal</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #2c3e50; /* Fundo preto */
      color: #ecf0f1; /* Texto branco */
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    header {
      background-color: #27ae60; /* Verde esmeralda */
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-bottom: 20px;
      width: 100%;
    }

    section {
      background-color: #34495e; /* Azul escuro */
      color: #ecf0f1;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      margin-bottom: 20px;
      width: 80%;
      max-width: 600px;
      text-align: left;
    }

    h1, h2, h3 {
      color: #ecf0f1;
    }

    p {
      line-height: 1.6;
    }

    a {
      color: #2ecc71; /* Verde claro */
      text-decoration: none;
      font-weight: bold;
    }

    .social-buttons {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      margin-top: 10px;
    }

    .social-buttons a {
      margin-bottom: 10px;
      display: inline-block;
      padding: 10px 15px;
      background-color: #3498db; /* Azul claro */
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
      font-weight: bold;
    }

    .youtube-button {
      background-color: #ff0000; /* Vermelho */
    }

    .instagram-button {
      background-color: #e84393; /* Rosa */
    }

    .arrows {
      font-size: 24px;
      margin-top: 10px;
      display: flex;
      align-items: center;
    }

    .arrow {
      animation: arrowAnimation 1s infinite;
      margin: 0 5px;
    }

    @keyframes arrowAnimation {
      0%, 100% {
        opacity: 0;
      }
      50% {
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Littlepeterzin</h1>
  </header>

  <section>
    <h2>Sobre Mim</h2>
    <p>Olá, meu nome é Littlepeterzin. Seja bem-vindo à minha página pessoal!</p>
  </section>

  <section>
    <h2>Interesses</h2>
    <p>Eu tenho uma paixão por Counter-Strike, séries, filmes e futebol. Nestas páginas, você encontrará informações e conteúdo relacionado a esses interesses.</p>
  </section>

  <section>
    <h2>Editor de Vídeo</h2>
    <p>Profissionalmente, sou um entusiasta de edição de vídeo. Trabalho com diversas ferramentas para criar conteúdo visualmente envolvente. Se você compartilha desse interesse ou precisa de serviços de edição, fique à vontade para <a href="https://www.youtube.com/@Littlepeterzin" target="_blank">entrar em contato!</a></p>
  </section>

  <section>
    <h2>Contato</h2>
    <p>Você pode me encontrar nas redes sociais:</p>
    <div class="social-buttons">
      <a class="twitter-button" href="https://twitter.com/peterzin999" target="_blank">Twitter</a>
      <a class="youtube-button" href="https://www.youtube.com/@Littlepeterzin" target="_blank">YouTube</a>
      <a class="instagram-button" href="https://www.instagram.com/peterjack.nxt/" target="_blank">Instagram</a>
    </div>
    <p>ou enviar um e-mail para <a href="mailto:joaovieiraujo@gmail.com">joaovieiraujo@gmail.com</a> para entrar em contato. Estou sempre aberto a novas conexões e oportunidades!</p>
    <div class="arrows">
      <span class="arrow">➡️</span>
      <span class="arrow">⬅️</span>
      <span class="arrow">➡️</span>
      <span class="arrow">⬅️</span>
    </div>
  </section>
</body>
</html>
