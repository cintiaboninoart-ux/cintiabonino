<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Cintia Bonino — Art & Illustration</title>

  <style>
    body {
      margin: 0;
      font-family: Helvetica, Arial, sans-serif;
      background: #f2f2f2;
      color: #111;
    }

    header {
      padding: 80px 40px;
      background: #000;
      color: #fff;
      text-align: center;
    }

    header h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      opacity: 0.8;
    }

    nav {
      background: #fff;
      padding: 20px 40px;
      position: sticky;
      top: 0;
      border-bottom: 1px solid #ddd;
    }

    nav a {
      margin-right: 20px;
      text-decoration: none;
      color: #000;
      font-weight: bold;
    }

    section {
      padding: 80px 40px;
      max-width: 1100px;
      margin: auto;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 30px;
    }

    .item {
      background: #ddd;
      height: 280px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 18px;
      color: #555;
    }

    footer {
      padding: 40px;
      text-align: center;
      background: #000;
      color: #fff;
    }
  </style>
</head>

<body>

  <header>
    <h1>Cintia Bonino</h1>
    <p>Illustration · Art · Visual storytelling</p>
  </header>

  <nav>
    <a href="#about">Sobre mí</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#projects">Proyectos</a>
    <a href="#contact">Contacto</a>
  </nav>

  <section id="about">
    <h2>Sobre mí</h2>
    <p>
      Soy artista visual e ilustradora. Trabajo con proyectos editoriales,
      culturales y experimentales. Mi obra explora la relación entre imagen,
      narrativa, identidad y emoción.
    </p>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>

    <div class="grid">
      <div class="item">Imagen 1</div>
      <div class="item">Imagen 2</div>
      <div class="item">Imagen 3</div>
      <div class="item">Imagen 4</div>
      <div class="item">Imagen 5</div>
      <div class="item">Imagen 6</div>
    </div>
  </section>

  <section id="projects">
    <h2>Proyectos</h2>
    <p>Próximamente: proyectos editoriales, culturales y colaborativos.</p>
  </section>

  <section id="contact">
    <h2>Contacto</h2>
    <p>
      Email: contacto@tudominio.com<br>
      Instagram: @tucuenta
    </p>
  </section>

  <footer>
    © 2026 — Cintia Bonino
  </footer>

</body>
</html>
