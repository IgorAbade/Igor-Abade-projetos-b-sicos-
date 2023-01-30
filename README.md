# Formulário simples 

<!DOCTYPE html>
  <html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-AU-Compatible" content="IE-edge">
    <meta name="viewport" content="width=device-width", initial-scale=1.0>
    <style>
    body{
  padding: 0;
  margin: 0;
  font-family: "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Geneva, Verdana, sans-serif;
  background: linear-gradient(0deg, rgba(12,189,167,1) 0%, rgba(245,252,22,1) 90%);
}

form{
  background-color: #F5F5F5;
  max-width: 450px;
  height: 190px;
  width: 60%;
  padding: 30px;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%,-50%);
  border-radius: 4px;
  border-style: ridge;
}

form h2{
  text-align: center;
  height: 50px;
}

form input[type=text],
form input[type=password]{
  width: 100%;
  height: 30px;
  border: 1px solid silver;
  padding-left: 5px;
  margin: 3px;
}

form input[type=submit]{
  width: 100%;
  margin: 3px;
  cursor: pointer;
  
}


    </style>
  </head>
  <body>
    <form>
      <h2> Login</h2>
      <input type="text" name="email" placeholder="email" required/>
      <input type="password" name="senha" placeholder="senha" required/>
      <input type="submit" name="enviar" value="Enviar" required/>
    </div>
    <script src="index.js"></script>
  </body>
  </html>
    
l
