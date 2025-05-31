
<!DOCTYPE html>
<html lang="es">
<head>
  <title>Mi Perfil GitHub - Estilo 90s</title>
  <style>
    body {
      background-color: #00FFFF;
      color: #000080;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    .container {
      border: 5px dashed #FF00FF;
      margin: 20px;
      padding: 20px;
      background-color: #FFFFE0;
    }
    h1 {
      text-shadow: 2px 2px #FF0000;
    }
    .gif {
      width: 100px;
      height: auto;
    }
    .button {
      background-color: #FFD700;
      border: 3px outset #FF4500;
      padding: 10px 20px;
      font-size: 16px;
      margin: 10px;
      cursor: pointer;
      text-decoration: none;
      color: black;
    }
    .button:hover {
      background-color: #FF69B4;
    }
    marquee {
      font-size: 18px;
      color: #008000;
    }
    footer {
      background-color: #000080;
      color: white;
      padding: 20px;
      margin-top: 40px;
    }
    .footer-gifs {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin-top: 10px;
    }
    .footer-gifs img {
      width: 88px;
      height: 31px;
      border: 2px inset #FFD700;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>¡Bienvenido a mi página retro!</h1>
    <img src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" class="gif" alt="GIF Retro">
    <p>Hola, soy <strong>TuNombre</strong> y este es mi perfil de GitHub con estilo noventero.</p>
    <marquee behavior="scroll" direction="left">¡Sígueme para más proyectos increíbles! 🚀</marquee>
    <a href="https://github.com/TuUsuario" class="button" target="_blank">Visita mi GitHub</a>
    <a href="mailto:tuemail@example.com" class="button">Contáctame</a>
    <br><br>
    <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" class="gif" alt="GIF Cool">
  </div>

  <footer>
    <p>Botones clásicos de los 90:</p>
    <div class="footer-gifs">
      <img src="https://www.gifss.com/computers/buttons/button1.gif" alt="Botón 1">
      <img src="https://www.gifss.com/computers/buttons/button2.gif" alt="Botón 2">
      <img src="https://www.gifss.com/computers/buttons/button3.gif" alt="Botón 3">
    </div>
  </footer>
</body>
</html>
