<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Planeta Fútbol 360</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(90deg, #1e3c72, #2a5298);
      color: #fff;
      padding: 30px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      letter-spacing: 2px;
    }
    header p {
      margin: 5px 0 0;
      font-style: italic;
    }
    .contenedor {
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }
    .noticia {
      background: #fff;
      margin: 20px 0;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.2s ease-in-out;
    }
    .noticia:hover {
      transform: translateY(-5px);
    }
    .noticia img {
      max-width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }
    .noticia h2 {
      color: #1e3c72;
      margin-bottom: 10px;
    }
    footer {
      background-color: #1e3c72;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Planeta Fútbol 360</h1>
    <p>Noticias y análisis del mejor fútbol</p>
  </header>

  <div class="contenedor">
    <!-- Noticia 1 -->
    <div class="noticia">
      <h2>Lewandowski se despide del Barcelona</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Robert_Lewandowski_2022.jpg" alt="Lewandowski en su última temporada con el Barça">
      <p>Robert Lewandowski ha decidido poner fin a su etapa en el FC Barcelona. Tras varias temporadas siendo el referente ofensivo del club, el delantero polaco busca nuevos retos en su carrera. Su salida marca el cierre de un ciclo en el que aportó goles, liderazgo y experiencia, dejando un vacío importante en la delantera culé.</p>
    </div>

    <!-- Noticia 2 -->
    <div class="noticia">
      <h2>Semifinales de Champions League 2026</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Champions_League_trophy.jpg" alt="Trofeo de la Champions League">
      <p>La Champions League 2026 está en su fase decisiva. PSG y Bayern protagonizan un duelo de gigantes, mientras que Atlético de Madrid y Arsenal luchan por un lugar en la final. Los partidos de ida dejaron emociones intensas y todo se definirá en la vuelta, con la expectativa de quién levantará la ansiada Orejona.</p>
    </div>

    <!-- Noticia 3 -->
    <div class="noticia">
      <h2>Messi revoluciona al Cornellà</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/8/8c/Lionel_Messi_2018.jpg" alt="Messi presidente del Cornellà">
      <p>En un movimiento inesperado, Lionel Messi ha adquirido el UE Cornellà y se ha convertido en su presidente. La operación ha generado un impacto inmediato: el club catalán ya supera al Espanyol en seguidores en redes sociales. Con Messi al mando, Cornellà inicia una nueva era de ambición y proyección internacional.</p>
    </div>
  </div>

  <footer>
    <p>© 2026 Planeta Fútbol 360 | Publicado con GitHub Pages</p>
  </footer>
</body>
</html>
