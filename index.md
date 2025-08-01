<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DapSound</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fdf6ec;
      color: #3a3a3a;
    }

    header {
      background-color: #d9cbb2;
      padding: 1.5rem;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }

    header img {
      max-width: 160px;
    }

    .hero {
      background-image: url('fondo-elegante.jpg');
      background-size: cover;
      background-position: center;
      padding: 100px 20px;
      text-align: center;
      color: #fff;
      position: relative;
    }

    .hero::after {
      content: '';
      background-color: rgba(0, 0, 0, 0.5);
      position: absolute;
      inset: 0;
      z-index: 0;
    }

    .hero h1 {
      position: relative;
      font-size: 3rem;
      margin: 0;
      z-index: 1;
    }

    .hero p {
      position: relative;
      font-size: 1.2rem;
      z-index: 1;
    }

    main {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .audio-card {
      background-color: #ffffff;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
      margin-bottom: 30px;
      display: flex;
      align-items: center;
      gap: 20px;
    }

    .audio-card img {
      width: 100px;
      height: 100px;
      border-radius: 8px;
      object-fit: cover;
    }

    .audio-card audio {
      width: 100%;
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      font-size: 0.9em;
      background-color: #d9cbb2;
      color: #3a3a3a;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logo DapSound" />
  </header>

  <section class="hero">
    <h1>Bienvenido a DapSound</h1>
    <p>Tu experiencia musical, más cerca que nunca</p>
  </section>

  <main>
    <div class="audio-card">
      <img src="portada1.jpg" alt="Portada 1" />
      <audio controls>
        <source src="audio1.mp3" type="audio/mp3" />
        Tu navegador no admite audio.
      </audio>
    </div>

    <div class="audio-card">
      <img src="portada2.jpg" alt="Portada 2" />
      <audio controls>
        <source src="audio2.mp3" type="audio/mp3" />
        Tu navegador no admite audio.
      </audio>
    </div>

    <p style="text-align: center; margin-top: 40px;">
      ¿Tienes dudas? Escríbenos a <a href="mailto:dani@dapsound.com">dani@dapsound.com</a>
    </p>
  </main>

  <footer>
    &copy; 2025 DapSound. Todos los derechos reservados.
  </footer>
</body>
</html>