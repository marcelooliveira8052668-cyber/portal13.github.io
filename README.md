# portal13.github.io

<!doctype html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <title>História</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <nav class="nav">
      <a href="index.html">Início</a>
    </nav>

    <section class="bloco">
      <h2>História Geral</h2>

      <p>
        Estudamos o passado, para entendermos nosso presente e construirmos um
        futuro
      </p>

      <img src="imagens/historia5.jpg" class="img-destaque" />
    </section>

    <section class="bloco">
      <h2>📥 Materiais</h2>

      <a href="arquivos/historia.docx" class="botao"> Baixar conteúdo </a>
    </section>
  </body>
</html>


<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Portal do Conhecimento</title>
  </head>

  <body>
    <!-- CLIMA -->
    <div class="clima-card">
      <div class="topo">
        <p class="local">Osasco, São Paulo</p>
        <p class="hora">19:20</p>
      </div>

      <div class="principal">
        <div class="icone">🌙</div>
        <div>
          <h1>23°C</h1>
          <p>Limpo</p>
          <span>Máx 31° • Mín 19°</span>
        </div>
      </div>

      <div class="dias">
        <div class="dia">
          <p>Hoje</p>
          <span>31° 19°</span>
        </div>
        <div class="dia">
          <p>Qua</p>
          <span>30° 19°</span>
        </div>
        <div class="dia">
          <p>Qui</p>
          <span>26° 19°</span>
        </div>
        <div class="dia">
          <p>Sex</p>
          <span>27° 18°</span>
        </div>
      </div>
    </div>

    <div class="banner">
      <img src="imagens/fundo.jpg" alt="" />
    </div>

    <section id="sobre" class="bloco">
      <h2>Portal do Conhecimento</h2>
      <p>História - Programação - Tecnologia</p>
    </section>

    <!-- ARTIGOS -->
    <section id="artigos" class="bloco">
      <h2>Meus Artigos</h2>

      <div class="cards">
        <div class="card">
          <a href="historia.html">
            <img src="https://via.placeholder.com/300x150" />
            <h3>História Geral e do Brasil</h3>
           <img src="imagens/foto4.jpg" alt="História">   
          </a>
        </div>

        <div class="card">
          <a href="programacao.html">
            <img src="https://via.placeholder.com/300x150" />
            <h3>Programação Front-end</h3>
            <img src="imagens/programacao2.jpg" alt="História"> 
            <img src="imagens/foto1.jpg" alt="História ">
            
            <img
          </a>
        </div>

        <div class="card">
          <a href="tecnologia.html">
            <img src="https://via.placeholder.com/300x150" />
            <h3>Tecnologia</h3>
          <img src="imagens/fundo.jpg" alt="História">
        </a>
        </div>

        <div class="card">
          <a href="contato.html">
            <img src="https://via.placeholder.com/150x100" />
            <h3>Contato</h3>
          </a>
        </div>
      </div>
    </section>

    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/SEU_VIDEO"></iframe>
      <h3>Aula de História</h3>
    </div>

    <footer>
      <p>Site criado por Marcelo Oliveira</p>
    </footer>
  </body>
</html>


<!doctype html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <title>Programação</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <nav class="nav">
      <a href="index.html">Início</a>
    </nav>

    <section class="bloco">
      <h2>💻 Programação</h2>

      <p>
        A programação permite criar sites, sistemas e aplicativos, utilizando
        linguagens como HTML, CSS e JavaScript.
      </p>

      <img src="imagens/programacao2.jpg" class="img-destaque" width="500">
    </section>

    <section class="bloco">
      <h2>📥 Materiais</h2>

      <a href="arquivos/programacao.docx" class="botao"> Baixar conteúdo </a>
    </section>
  </body>
</html>


<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Tecnologia</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<nav class="nav">
  <a href="index.html">Início</a>
</nav>

<section class="bloco">

  <h2>Tecnologia-moderna</h2>

  <p>
   A evolução da tecnologia no mundo.
  </p>



<img src="imagens/tecnologia3.jpg" alt="Imagem de tecnologia" width="500">

<a href="arquivos/tecnologia.docx" download>
  📥 Baixar material em Word
</a>


</body>
</html>



* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #0f2027;
  color: white;
}

/* BANNER */
.banner {
  position: relative;
}

.banner img {
  width: 100%;
  height: 300px;
  object-fit: cover;
}

.banner::after {
  
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 2em;
  color: rgb(241, 219, 16);
  font-weight: bold;
}

/* BLOCOS */
.bloco {
  padding: 40px;
  text-align: center;
}

/* TÍTULOS */
h2 {
  margin-bottom: 20px;
}

/* CARDS */
.cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card {
  background: #1c1c1c;
  border-radius: 10px;
  width: 250px;
  overflow: hidden;
  transition: 0.3s;
}

.card img {
  width: 100%;
}

.card h3 {
  padding: 15px;
}

.card a {
  text-decoration: none;
  color: white;
}

.card:hover {
  transform: scale(1.05);
  background: #2a2a2a;
}

/* FOOTER */
footer {
  background: #000;
  text-align: 10px;
  padding: 20px;
  margin-top: 40px;
}


.tempo {
  position: fixed;
  top: 20px;
  right: 20px;
  background: rgba(0,0,0,0.6);
  padding: 15px;
  border-radius: 10px;
  color: white;
  font-family: Arial;
  text-align: center;
  backdrop-filter: blur(8px);
  box-shadow: 0 0 10px rgba(0,0,0,0.5);
}

.temperatura {
  width: 250px;
  position: fixed;
  right: 20px;
  top: 100px;
}

.clima-card {
  position: fixed;   /* 🔥 isso tira do fluxo da página */
  top: 20px;
  right: 20px;

  width: 240px;
  padding: 20px;

  background: linear-gradient(135deg, #0a192f, #112240);
  color: white;

  border-radius: 20px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.3);

  z-index: 9999; /* 🔥 garante que fica na frente do banner */
}

/* topo */
.topo {
  display: flex;
  justify-content: space-between;
  font-size: 14px;
  opacity: 0.8;
}

/* parte principal */
.principal {
  display: flex;
  align-items: center;
  margin: 20px 0;
}

.icone {
  font-size: 50px;
  margin-right: 15px;
}

.principal h1 {
  margin: 0;
  font-size: 40px;
}

.principal span {
  font-size: 12px;
  opacity: 0.7;
}

/* previsão dias */
.dias {
  display: flex;
  justify-content: space-between;
  margin-top: 15px;
}

.dia {
  background: #334155;
  padding: 10px;
  border-radius: 10px;
  text-align: center;
  font-size: 12px;
  width: 60px;
}

.dia p {
  margin-bottom: 5px;
}

.contato {
  padding: 60px 20px;
  background: #0a192f;
  color: white;
  text-align: center;
}

.container-contato {
  display: flex;
  justify-content: center;
  gap: 40px;
  flex-wrap: wrap;
  margin-top: 30px;
}

.form-contato {
  display: flex;
  flex-direction: column;
  width: 100px;
}

.form-contato input,
.form-contato textarea {
  margin-bottom: 15px;
  padding: 12px;
  border: none;
  border-radius: 8px;
}

.form-contato button {
  padding: 12px;
  background: #00bcd4;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s;
}

.form-contato button:hover {
  background: #0097a7;
}

.whatsapp-box a {
  display: inline-block;
  margin-top: 15px;
  padding: 12px 20px;
  background: #25D366;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  font-weight: bold;
}

.whatsapp-box a:hover {
  background: #1ebe5d;
}

/* CAIXA DE CLIMA MODERNA */
.clima-card {
  position: fixed;
  top: 20px;
  right: 20px;

  width: 240px;
  padding: 20px;

  background: linear-gradient(135deg, #0a192f, #112240);
  color: white;

  border-radius: 20px; /* 🔥 deixa bem redondo */
  box-shadow: 0 10px 25px rgba(0,0,0,0.3);

  font-family: Arial, sans-serif;
}

/* TOPO */
.topo {
  display: flex;
  justify-content: space-between;
  font-size: 14px;
  opacity: 0.8;
}

/* PARTE PRINCIPAL */
.principal {
  display: flex;
  align-items: center;
  gap: 15px;
  margin: 15px 0;
}

.icone {
  font-size: 40px;
}

/* TEMPERATURA */
.principal h1 {
  margin: 0;
  font-size: 32px;
}

/* DESCRIÇÃO */
.principal p {
  margin: 0;
  font-size: 14px;
  opacity: 0.8;
}

/* MÁX E MÍN */
.principal span {
  font-size: 12px;
  opacity: 0.6;
}

/* DIAS */
.dias {
  display: flex;
  justify-content: space-between;
  margin-top: 15px;
}

.dia {
  text-align: center;
  font-size: 12px;
  background: rgba(255,255,255,0.05);
  padding: 8px;
  border-radius: 10px;
  width: 50px;
}

.dia p {
  margin: 0;
}

.dia span {
  font-size: 11px;
  opacity: 0.8;
}

.clima-card:hover {
  transform: scale(1.05);
  transition: 0.3s;
}

.video-card {
  width: 300px;
  margin: 20px;
  text-align: center;
}

.video-card iframe {
  width: 100%;
  height: 170px;
  border-radius: 15px;
}

<section id="contato" class="contato">

  <h2>📞 Fale Comigo</h2>
  <p>Tem dúvidas ou quer aprender mais? Entre em contato!</p>

  <div class="container-contato">

    <!-- FORMULÁRIO -->
    <form class="form-contato">
      <input type="text" placeholder="Seu nome" required>
      <input type="email" placeholder="Seu e-mail" required>
      <textarea placeholder="Digite sua mensagem..." required></textarea>

      <button type="submit">Enviar Mensagem</button>
    </form>

    <!-- WHATSAPP -->
    <div class="whatsapp-box">
      <h3>Ou fale direto comigo:</h3>
      <a href="https://wa.me/5511942038103" target="_blank">
        💬 WhatsApp
      </a>
    </div>

  </div>

</section>
