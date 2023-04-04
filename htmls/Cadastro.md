<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script>
      var elementoDataHora = document.getElementById("dataHora");
      setInterval(function(dataHoraAtual) {
        var dataHoraAtual = new Date(dataHoraAtual);
        elementoDataHora.innerHTML = "Data e hora atuais: " + dataHoraAtual.toLocaleString(dataHoraAtual);
      }, 1000);
    </script>
    <title>aula 22-03</title>
</head>
<body align="center" background="download/fundo.png">
  <div text-align: center>
  <table></table><br>
    <table border="2" width="1400"><h1>FORMULARIO AULA</h1><p id="dataHora"></p></p>
    </table>

    <li type="disc"><h3>Login user</h3></li>
        <form action="">
  <Label for="log">Login:</Label><br>
  <input type="text" nome="" id=""><br>
  <label for="pass">Senha:</label><br>
  <input type="password" name="" id=""><br>
  <input type="submit" value="Enviar"><br>
  </div>
  <h3>incrição em disciplina</h3>
  <label for="Linguagem"> Linguagem C</label>
  <input type="checkbox" name="lang" id="C"><br>
  <label for="C++"> Lingguagem C++</label>
  <input type="checkbox" name="lang" id="C++>"><br>
  <label for="Pascal"> Pascal </label>
  <input type="checkbox" name="lang" id="Pascal"><br>
  <br><br>
  <h3>Sexo</h3>
  <label for="M"> Masc</label>
  <input type="radio" name="gen"value="M"><br>
  <label for="F"> Fem</label>
  <input type="radio" name="gen"value="F"><br>
  <label for="Outro"> Outro</label>
  <input type="checkbox" name="gen"value="Outro"><br>
  <label for="E">Estados</label>
  <Select name="teste" id="E">
    <option value="PR">PR</option>
    <option value="SC">SC</option>
    <option value="RJ">RJ</option>
  </Select>
<br><br>
<h3> Grau de ensino</h3>
<label for="E">Escolaridade</label>
  <Select name="teste" id="E">
    <option value="Doutorado">Doutorado</option>
    <option value="Mestrado">Mestrado</option>
    <option value="Graduação">Graduação</option>
    <option value="Ensino médio">Ensino médio</option>
    <option value="Ensino Básico">Ensino Básico</option>
  </Select>
<br><br>
<input type="submit">
</form>

</body>

