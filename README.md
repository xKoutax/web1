<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Hacked Page - By Tätsú_</title>
  
  <!-- Google Font: Roboto -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;600;700&display=swap" rel="stylesheet" />
  
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #000000; /* negro puro */
      color: #ddd; /* gris claro */
      font-family: 'Roboto', Arial, sans-serif;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      position: relative; /* necesario para posicionamiento absoluto hijo */
    }

    .title {
      color: #bbbbbb;
      font-size: 3.2em;  /* tamaño reducido */
      font-weight: 600;
      margin: 20px 0;
      max-width: 90vw; /* para que no se desborde */
      word-wrap: break-word;
    }

    .hacked {
      color: #a0a0a0;
      font-size: 2.8em;
      margin: 10px 0;
      font-weight: 500;
    }

    .by {
      font-size: 3.8em;
      color: #8fa8c8; /* azul suave */
      margin-bottom: 30px;
      font-weight: 700;
    }

    .logo img {
      width: 450px;
      max-width: 90%;
      border: 2px solid #8fa8c8;
      border-radius: 12px;
      box-shadow: 0 0 30px #8fa8c8;
    }

    .msg {
      color: #cfcfcf;
      font-size: 1.6em;
      margin-top: 40px;
      padding: 0 20px;
      font-weight: 400;

      width: 100vw;           /* ancho total de la ventana */
      max-width: 100%;        /* no exceder la ventana */
      box-sizing: border-box; /* padding no aumenta ancho */
      text-align: center;     /* texto centrado */
      user-select: none;
    }

    .alert {
      color: #9abedc;
      font-size: 1.9em;
      margin-top: 20px;
      font-weight: 500;
    }

    .illusion {
      position: absolute;
      bottom: 15px;
      right: 15px; /* esquina inferior derecha */
      color: #b0c4de;
      font-size: 1.3em;
      font-style: italic;
      font-weight: 400;
      max-width: 40%;
      text-align: right;
      user-select: none;
      opacity: 0.7;
      letter-spacing: 0.06em;
      line-height: 1.2em;
    }

    /* Ajustes para pantallas pequeñas */
    @media (max-width: 600px) {
      .illusion {
        max-width: 70%;
        font-size: 1em;
        bottom: 10px;
        right: 10px;
      }
    }
  </style>
</head>
<body>

  <div class="title">Access Exploited</div>
  <div class="hacked">:: HACKED BY ::</div>
  <div class="logo">
    <img src="https://github.com/xKoutax/portfolio/blob/master/assets/images/tats.jpg?raw=true" alt="Logo" />
  </div>
  <div class="by">Tätsú_</div>
  <div class="msg">
    Sorry Admin, I Was On Your System. By Anonymous, PLEASE CHECK AND PATCH YOUR SECURITY!
  </div>

  <div class="alert">- Ethical Hacking -</div>

  <div class="illusion">~ SECURITY IS JUST AN ILLUSION ~</div>

</body>
</html>
