<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>German Barandica | Creative Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <style>
    :root {
      --dark: #0f0f0f;
      --light: #f5f5f5;
      --gray: #8a8a8a;
      --accent: #cfcfcf;
    }

    body {
      margin: 0;
      font-family: "Inter", Arial, sans-serif;
      background: var(--dark);
      color: white;
    }

    header {
      padding: 120px 20px;
      text-align: center;
      background: linear-gradient(180deg, #0f0f0f, #161616);
    }

    header h1 {
      font-size: 48px;
      margin: 0;
      letter-spacing: 1px;
    }

    header p {
      color: var(--accent);
      font-size: 18px;
      margin-top: 15px;
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
    }

    section {
      max-width: 1200px;
      margin: auto;
      padding: 90px 20px;
    }

    h2 {
      font-size: 32px;
      margin-bottom: 40px;
    }

    .sub {
      color: var(--gray);
      font-size: 15px;
      margin-top: -25px;
      margin-bottom: 40px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .card {
      background: #161616;
      padding: 25px;
      border-radius: 12px;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    .card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }

    .card h3 {
      margin-top: 0;
    }

    .card p {
      color: var(--gray);
      font-size: 14px;
      line-height: 1.6;
    }

    .tools {
      color: var(--gray);
      font-size: 15px;
      line-height: 1.8;
    }

    footer {
      background: #0a0a0a;
      text-align: center;
      padding: 40px 20px;
      color: var(--gray);
      font-size: 14px;
    }

    a {
      color: white;
      text-decoration: none;
      border-bottom: 1px solid var(--gray);
    }
  </style>
</head>

<body>

<header>
  <h1>German Barandica</h1>
  <p>
    Visualización 3D · Renders para Eventos · Producción Ejecutiva<br>
    3D Visualization · Event Renders · Executive Production
  </p>
</header>

<section>
  <h2>Sobre mí / About me</h2>
  <p class="sub">Perfil creativo enfocado en visualización y eventos</p>
  <p>
    Profesional creativo con experiencia en renders 3D para eventos,
    stands y espacios comerciales, así como producción audiovisual y
    gestión de proyectos.<br><br>
    Creative professional specialized in 3D visualization for events,
    stands and commercial spaces, with experience in audiovisual
    production and project management.
  </p>
</section>

<section>
  <h2>Servicios / Services</h2>
  <p class="sub">Prioridad en renders y eventos</p>

  <div class="grid">
    <div class="card">
      <h3>Renders para Eventos</h3>
      <p>
        Visualización 3D de stands, ferias, activaciones de marca y
        espacios efímeros.<br><br>
        3D visualization for stands, fairs and brand activations.
      </p>
    </div>

    <div class="card">
      <h3>Visualización Arquitectónica</h3>
      <p>
        Renders realistas para espacios comerciales y conceptuales.<br><br>
        High-quality architectural and conceptual renders.
      </p>
    </div>

    <div class="card">
      <h3>Producción Audiovisual</h3>
      <p>
        Edición de video, motion graphics y contenido digital.<br><br>
        Video editing, motion graphics and digital content.
      </p>
    </div>

    <div class="card">
      <h3>Producción Ejecutiva</h3>
      <p>
        Planificación, coordinación y ejecución de proyectos creativos.<br><br>
        Creative project planning and execution.
      </p>
    </div>
  </div>
</section>

<section>
  <h2>Portafolio / Portfolio</h2>
  <p class="sub">Renders & eventos</p>

  <div class="grid">
    <div class="card">
      <img src="imagenes/render1.jpg" alt="Event Render">
      <p>Render de stand para evento corporativo</p>
    </div>

    <div class="card">
      <img src="imagenes/render2.jpg" alt="3D Render">
      <p>Visualización 3D de espacio para feria</p>
    </div>

    <div class="card">
      <img src="imagenes/render3.jpg" alt="Exhibition">
      <p>Concepto de exhibición y activación de marca</p>
    </div>
  </div>
</section>

<section>
  <h2>Herramientas / Tools</h2>
  <p class="tools">
    SketchUp · Lumion · KeyShot · Adobe Illustrator · Photoshop ·
    Premiere Pro · After Effects · Filmora
  </p>
</section>

<section>
  <h2>Contacto / Contact</h2>
  <p>Email: <strong>tucorreo@email.com</strong></p>
  <p>
    <a href="#">LinkedIn</a> ·
    <a href="#">Workana</a> ·
    <a href="#">Behance</a>
  </p>
</section>

<footer>
  © 2026 · German Barandica · Creative Portfolio
</footer>

</body>
</html>
