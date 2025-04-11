<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Socialicity</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fdf6f0;
      color: #333;
      margin: 0;
      padding: 0;
      transition: background-color 0.3s, color 0.3s;
    }

    header {
      background-color: #a3c4f3;
      color: #fff;
      padding: 1.5rem;
      text-align: center;
      border-radius: 0 0 20px 20px;
    }

    h1 {
      font-size: 2.5rem;
      margin: 0;
    }

    nav {
      margin-top: 1rem;
    }

    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #fff;
      font-weight: bold;
    }

    .content {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }

    .content h2 {
      color: #52796f;
    }

    .sensory-toggle {
      position: fixed;
      top: 1rem;
      right: 1rem;
      background: #f7d9d9;
      border: none;
      padding: 0.5rem 1rem;
      font-size: 1rem;
      border-radius: 8px;
      cursor: pointer;
    }

    .sensory-mode {
      background-color: #ffffff !important;
      color: #111 !important;
    }
  </style>
</head>
<body>
  <button class="sensory-toggle" onclick="toggleSensory()">Modo sensorial suave</button>
  <header>
    <h1>Socialicity</h1>
    <nav>
      <a href="#quienes">Quiénes somos</a>
      <a href="#objetivo">Objetivo</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <div class="content">
    <section id="quienes">
      <h2>Quiénes somos</h2>
      <p>Socialicity es una comunidad creada con cariño para quienes sienten que socializar no siempre es fácil. Un espacio suave, seguro y libre para compartir, expresarte y conectar.</p>
    </section>

    <section id="objetivo">
      <h2>¿Cuál es nuestro propósito?</h2>
      <p>Ofrecer un entorno amable donde las personas con intereses nerd, introvertidas o neurodivergentes puedan conectar sin presiones ni máscaras. Aquí todo el mundo vale tal como es. 💛</p>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <p>¿Ideas, sugerencias, saludos? ¡Queremos escucharte!</p>
      <p><a href="mailto:contacto@socialicity.com">contacto@socialicity.com</a></p>
    </section>
  </div>

  <script>
    function toggleSensory() {
      document.body.classList.toggle('sensory-mode');
    }
  </script>
</body>
</html>
