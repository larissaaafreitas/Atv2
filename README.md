<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TechFuture Summit</title>
  <link rel="icon" href="https://img.freepik.com/vetores-premium/ilustracao-do-logotipo-retratando-o-design-do-logotipo-do-metaverso-web3-com-vetor-pro_1249511-2109.jpg?semt=ais_hybrid&w=740" type="image/jpg">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-image: url('https://c4.wallpaperflare.com/wallpaper/219/288/895/space-spiral-swirl-swirls-wallpaper-preview.jpg');
 color: #000000;
 background-size: 50%;
    }

    .centralizar {
      max-width: 960px;
      margin: auto;
      padding: 20px;
    }

    header {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(90deg, #4f00bc, #8e2de2);
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0,0,0,0.3);
      margin-bottom: 40px;
    }

    header h1 {
      font-size: 3rem;
      color: #ffffff;
    }

    section {
      background-color: #ffffff;
      color: #333;
      border-radius: 10px;
      padding: 30px;
      margin-bottom: 30px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: #4f00bc;
      margin-bottom: 15px;
    }

    p, li {
      font-size: 16px;
    }

    .palestrante {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      align-items: center;
      margin-bottom: 30px;
    }

    .palestrante img {
       width: 150px; 
height: 200px; 
border-radius: 50%; 
  object-fit: cover;
    }

    .info-palestrante {
      flex: 1;
    }

    .nome {
      font-weight: bold;
      color: #8e2de2;
      font-size: 1.2em;
    }

    form label {
      display: block;
      margin: 15px 0 5px;
      font-weight: bold;
    }

    input[type="text"],
    input[type="email"] {
      width: 100%;
      padding: 10px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 1em;
    }

    

    button {
      margin-top: 20px;
      padding: 12px 30px;
      background-color: #4f00bc;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 1em;
      cursor: pointer;
     
    }

    button:hover {
      background-color: #370082;
    }

    @media screen and (max-width: 600px) {
      .palestrante {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <div class="centralizar">
    <header>
      <h1>TechFuture Summit</h1>
    </header>

    <section>
      <h2>Sobre o Evento</h2>
      <p><strong>Data:</strong> 4 de setembro de 2025</p>
      <p><strong>Local:</strong> Cidade da Música, Salvador-BA</p> <br>
      <p>A TechConnect é o lugar perfeito para quem curte tecnologia e quer ficar por dentro das novidades.
         Juntamos desenvolvedores, designers e muita gente que entende do assunto para trocar ideias e falar das
          tendências mais atuais da tecnologia. É uma oportunidade incrível para aprender, 
        fazer networking e se inspirar para criar coisas novas. Se inscreva para participar!</p>
    </section>

    <section>
      <h2>Palestrantes</h2>

      <div class="palestrante">
        <img src="https://img.freepik.com/fotos-gratis/mulher-asiatica-satisfeita-com-um-sorriso-largo-penteado-curto-vestido-casualmente-senta-se-a-mesa-do-cafe-gosta-do-tempo-de-lazer-linda-mulher-japonesa-descansando-sozinha-em-restaurante_273609-2712.jpg" alt="Foto da palestrante Saori">
        <div class="info-palestrante">
          <p class="nome">Saori Hoshimoto</p>
          <p>Desenvolvedora sênior especializada em IA e sistemas autônomos, com mais de 10 anos de experiência no mercado.</p>
        </div>
      </div>

      <div class="palestrante">
        <img src="https://img.freepik.com/fotos-gratis/mulher-de-vista-superior-com-penteado-afro_23-2150677192.jpg?semt=ais_hybrid&w=740" alt="Foto de uma mulher asiatica">
        <div class="info-palestrante">
          <p class="nome">Helena Souza Matos</p>
          <p>UX designer e especialista em acessibilidade digital. Atua como consultora em projetos de grande impacto.</p>
        </div>
      </div>

      <div class="palestrante">
        <img src="https://i.pinimg.com/736x/42/27/85/422785b3a4100bb7e9de4dd910eba041.jpg" alt="Foto de uma mulher ">
        <div class="info-palestrante">
          <p class="nome">Kira Gomes</p>
          <p>Transforma ideias em marcas memoráveis. Brand Designer apaixonada por construir conexões visuais.</p>
        </div>
      </div>

      <div class="palestrante">
        <img src="https://png.pngtree.com/png-clipart/20241105/original/pngtree-professional-black-man-png-image_16684393.png" alt="Foto de uma mulher ">
        <div class="info-palestrante">
          <p class="nome">Caio Menezes</p>
          <p> Sua missão como DevOps Engineer é tornar a entrega de software eficiente, segura e automatizada.</p>
        </div>
      </div>
    </section>

    <section>
      <h2>Inscreva-se</h2>
      <form>
        <label for="nome">Nome completo:</label>
        <input type="text" id="nome" name="nome" required>

        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email" required>

        <label>Tipo de ingresso:</label>
        <label><input type="radio" name="ingresso" value="Presencial" required> Presencial</label>
        <label><input type="radio" name="ingresso" value="Online"> Online</label>

        <label><input type="checkbox" required> Aceito os termos e condições</label>

        <button type="submit">Enviar Inscrição</button>
      </form>
    </section>
  </div>
</body>
</html>
