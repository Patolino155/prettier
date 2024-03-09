<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta property="og:url" content="https://brigadeirogourmet.com.br/" />
    <meta property="og:type" content="website" />
    <meta property="og:title" content="Brigadeiro Gourmet" />
    <meta property="og:description" content="Receitas deliciosas de brigadeiro gourmet." />
    <meta property="og:image" content="https://brigadeirogourmet.com.br/images/brigadeiro.jpg" />  
    <meta name="description" content="Brigadeiro Gourmet">
    <meta name="keywords" content="brigadeiro, receita, doce">
    <meta name="author" content="Brigadeiro Gourmet">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brigadeiro Gourmet</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="shortcut icon" href="fav.png">
    <style>
      * {
          color: #111111;
      }
      body {
          background: #FFFFFF;
      }
      .logo {
          width: 100px;
      }
      .progress {
          background: #27963C;
      }
      .bar {
          background: #F5F5F5;
      }
      .option {
          color: #111111;
          background: #E6E6E6;
          border: solid 1px #27963C;
      }
      .option:hover {
          color: #F5F5F5;
          background: #27963C;
          border: solid 1px transparent;
      }
      .loading {
          background: #EEEEEE;
      }
      .loading-title, .loading-text {
          color: #111111;
      }
      .loading-bar-progress {
          background: #27963C;
          animation: loading-bar 6s ease-in;
          animation-fill-mode: forwards;
          animation-delay: 500ms;
      }
      .loading-bar {
          background: #F5F5F5;
      }
      .disclaimer, .disclaimer a, .disclaimer a:visited {
          color: ;
      }
      @keyframes progress {
          0%      {width: 0%;}
          100%    {width: 3.8461538461538%;}
      }
    </style>
  </head> 
  <body>
    <header>
      <div class="content center">
        <img class="logo" src="logobrigadeiro.png" alt="Brigadeiro Gourmet" />
        <div class="bar">
          <div class="progress"></div>
        </div>
      </div>
    </header>
    
    <section>
      <div class="content center">
        <h1>Descubra novas receitas de brigadeiro gourmet!</h1>
        <span class="description">Escolha uma categoria para começar:</span>
        <div class="layout1">
          <div class="askrow">
            <a class="option" href="receitas/chocolate-amargo.html">Chocolate Amargo<img src="imagens/chocolate-amargo.jpg" alt="Chocolate Amargo" /></a>
            <a class="option" href="receitas/chocolate-branco.html">Chocolate Branco<img src="imagens/chocolate-branco.jpg" alt="Chocolate Branco" /></a>
          </div>
          <div class="askrow">
            <a class="option" href="receitas/leite-condensado-tradicional.html">Leite Condensado Tradicional<img src="imagens/leite-condensado-tradicional.jpg" alt="Leite Condensado Tradicional" /></a>
            <a class="option" href="receitas/vegano-sem-acucar.html">Vegano sem Açúcar<img src="imagens/vegano-sem-acucar.jpg" alt="Vegano sem Açúcar" /></a>
          </div>
        </div>
      </div>
    </section>
  </body>
</html>
HTMLCopiar código
