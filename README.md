<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Plaza Zacatecas</title>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet" />
  <style>
    /* Reset */
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      background: linear-gradient(135deg, #121212 0%, #1f1f1f 100%);
      color: #ccc;
      font-family: 'Press Start 2P', cursive;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }
    header {
      background: linear-gradient(90deg, #0d3b66, #d72631);
      padding: 3rem 1rem;
      text-align: center;
      color: #eee;
      text-shadow:
        0 0 5px #d72631,
        0 0 15px #d72631,
        0 0 20px #0d3b66,
        0 0 40px #0d3b66;
      letter-spacing: 3px;
      font-size: 2.5rem;
      user-select: none;
    }
    nav {
      background-color: #222;
      display: flex;
      justify-content: center;
      gap: 3rem;
      padding: 1.5rem 0;
      box-shadow: 0 0 15px #0d3b66 inset;
      user-select: none;
    }
    nav a {
      color: #eee;
      text-decoration: none;
      font-weight: bold;
      font-size: 0.85rem;
      text-transform: uppercase;
      padding: 0.3rem 0.8rem;
      border-radius: 4px;
      transition: all 0.3s ease;
      box-shadow: 0 0 5px transparent;
    }
    nav a:hover, nav a:focus {
      color: #d72631;
      box-shadow:
        0 0 8px #d72631,
        0 0 15px #0d3b66;
      outline: none;
    }
    main {
      flex-grow: 1;
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    section {
      background: #1a1a1a;
      margin-bottom: 2rem;
      padding: 2rem;
      border-radius: 12px;
      box-shadow:
        0 0 10px #0d3b66,
        0 0 20px #d72631 inset;
      transition: box-shadow 0.3s ease;
    }
    section:hover {
      box-shadow:
        0 0 20px #0d3b66,
        0 0 40px #d72631 inset;
    }
    h2 {
      color: #d72631;
      text-shadow:
        0 0 3px #d72631,
        0 0 7px #0d3b66;
      margin-top: 0;
      font-size: 1.8rem;
      user-select: none;
    }
    p {
      line-height: 1.6;
      font-size: 0.9rem;
    }
    footer {
      background-color: #111;
      text-align: center;
      padding: 1rem;
      font-size: 0.75rem;
      color: #555;
      user-select: none;
      box-shadow: inset 0 0 15px #0d3b66;
    }
    /* Animación en header */
    @keyframes glow {
      0%, 100% {
        text-shadow:
          0 0 5px #d72631,
          0 0 15px #d72631,
          0 0 20px #0d3b66,
          0 0 40px #0d3b66;
      }
      50% {
        text-shadow:
          0 0 8px #ff3c3c,
          0 0 25px #0f72c8,
          0 0 35px #0f72c8,
          0 0 55px #ff3c3c;
      }
    }
    header h1 {
      animation: glow 3s ease-in-out infinite;
    }
    /* Botones - Si quieres agregar luego */
    button {
      background: linear-gradient(45deg, #0d3b66, #d72631);
      border: none;
      color: #eee;
      padding: 0.7rem 1.5rem;
      font-family: 'Press Start 2P', cursive;
      font-size: 0.8rem;
      cursor: pointer;
      border-radius: 8px;
      box-shadow: 0 0 10px #d72631;
      transition: box-shadow 0.3s ease;
      user-select: none;
    }
    button:hover {
      box-shadow: 0 0 20px #d72631, 0 0 30px #0d3b66;
    }
  </style>
</head>
<body>
  <header>
    <h1>Plaza Zacatecas</h1>
  </header>
  <nav>
    <a href="#inicio" tabindex="1">Mantenimientos</a>
    <a href="#sobre" tabindex="2">CCTV</a>
    <a href="#contacto" tabindex="3">Minuta</a>
  </nav>
  <main>
    <section id="Mantenimientos" tabindex="4">
      <h2>Mantenimientos preventivos</h2>
      <p>Calendario</p>
    </section>
    <section id="CCTV" tabindex="5">
      <h2>Validacion COP y ACC</h2>
      <p>Evidencias del centro de control incluyendo ACC</p>
    </section>
    <section id="Minuta Mensual" tabindex="6">
      <h2>Minuta Mensual</h2>
      <p>Mayo</p>
      <p>Junio</p>
    </section>
  </main>
  <footer>
    &copy; 2025 Plaza Zacatecas • 
  </footer>
</body>
</html># plaza-zacatecas
