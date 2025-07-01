# Guhorlando.github.io
Neste repositório estará um site de usuário

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Gustavo Orlando - Sobre Mim</title>
  <style>
    :root {
      --bg-color: #1a1b26;
      --card-color: #24283b;
      --text-color: #c0caf5;
      --accent: #7aa2f7;
      --title: #bb9af7;
      --highlight: #9ece6a;
    }

    body {
      margin: 0;
      padding: 20px;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
    }

    .container {
      max-width: 900px;
      margin: auto;
    }

    .profile {
      display: flex;
      align-items: center;
      gap: 20px;
      margin-bottom: 30px;
    }

    .profile img {
      width: 130px;
      height: 130px;
      object-fit: cover;
      border-radius: 100%;
      border: 3px solid var(--accent);
    }

    h1 {
      color: var(--accent);
      font-size: 2.2em;
    }

    h2 {
      color: var(--title);
      margin-top: 30px;
      border-bottom: 2px solid var(--accent);
      padding-bottom: 5px;
    }

    section {
      background-color: var(--card-color);
      border-radius: 12px;
      padding: 20px;
      margin-top: 20px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    }

    ul {
      padding-left: 20px;
    }

    ul li {
      margin-bottom: 10px;
      list-style-type: "➤ ";
      padding-left: 8px;
    }

    .footer {
      background-color: #1f2335;
      margin-top: 40px;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      color: #7aa2f7;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="container">

    <div class="profile">
      <img src="guh.jpg" alt="Foto de Gustavo Orlando">
      <div>
        <h1>Gustavo Orlando</h1>
        <p>Estudante de Ciência da Computação na UNIFAL</p>
        <p>Idade: 19 anos</p>
      </div>
    </div>

    <section>
      <h2>🎧 Meus Interesses</h2>
      <ul>
        <li>Ouvir músicas de diversos estilos</li>
        <li>Videogames e tecnologia</li>
        <li>Ir a festas e sair com a família</li>
      </ul>
    </section>

    <section>
      <h2>🥁 Atividades e Estilo de Vida</h2>
      <ul>
        <li>Toco bateria</li>
        <li>Curto treinar pesado na academia</li>
        <li>Curto ficar sozinho, às vezes</li>
      </ul>
    </section>

    <section>
      <h2>📚 Educação</h2>
      <ul>
        <li>Curso: Ciência da Computação</li>
        <li>Universidade Federal de Alfenas (UNIFAL)</li>
      </ul>
    </section>

    <div class="footer">
      <p>Você pode me encontrar por aí curtindo um som, jogando alguma coisa ou levantando uns pesos!</p>
    </div>

  </div>
</body>
</html>
