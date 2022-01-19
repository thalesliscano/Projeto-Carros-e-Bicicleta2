# Zona-de-treino
<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Document</title>
</head>

<body>
  <h1 id="titulo">Carros e Bicicletas</h1>

  <div class="bloco1">
    <h2 class="subtitulo">Carro: <span>R$ 1999</span></h2>
    <p>Carros modelo <span>2045</span>, com <span>200km</span> rodados</p>
    <span class="botao1"><a href="/">Comprar Carro</a></span>
  </div>

  <div class="bloco2">
    <h2 class="subtitulo">Bicicleta: <span>R$ 199</span></h2>
    <p> Carros modelo <span>2050</span>, com <span>20km</span> rodados </p>
    <span class="botao2"><a href="/">Comprar Bicicleta</a></span>

  </div>
</body>


</html>
-----------------------------------------------------------------------------------------------------------------------

css

body {
  margin: 0px;
  flex-direction: row;
  font-family: Arial;
}
#titulo {
  text-align: right;
}
.subtitulo {
  color: white;
  margin: 10px;
}
.bloco1 {
  width: 800px;
  height: 120px;
  padding: 35px;
  margin: 15px;
  margin-left: 400px;
  border-radius: 4px;
  background: #000;
  box-align: center;
  text-align: justify;
  flex-direction: row;
  justify-content: space-around;
}
.bloco2 {
  width: 800px;
  height: 120px;
  padding: 35px;
  margin: 10px;
  margin-left: 400px;
  border-radius: 4px;
  background: #000;
  text-align: justify;
}
div span {
  color: #febe01;
  border-radius: 4px;
}
.botao1 {
  color: #320;
  background-color: #febe01;
  width: 115px;
  height: 25px;
  padding: 6px;
  margin: 15px;
  display: inline-block;
}
.botao2 {
  color: #332200;
  background-color: #febe01;
  width: 140px;
  height: 25px;
  padding: 6px;
  margin: 15px;
  display: inline-block;
}

div p {
  color: #b2b2b2;
  text-align: start, center;
  padding: px;
  margin: 10px;
}
a {
  text-decoration: none;
  color: inherit;
}
/* button {
  display: inherit;
  background-color: #febe01;
  border-radius: 4px;

} */

