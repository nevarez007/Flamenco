<html lang="es">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
  <header>
    <h1>Clase de Flamenco</h1>
    <nav>
      <a href="index.html">Inicio</a>
      <a href="clases.html">Clases</a>
      <a href="estilos.html">Estilos</a>
      <a href="contacto.html">Contacto</a>
      <a href="https://es.wikipedia.org/wiki/Flamenco" target="_blank">¿Qué es el Flamenco?</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>¿Qué es el Flamenco?</h2>
      <p>El flamenco es un estilo de danza y música tradicional originario del sur de España. Se caracteriza por movimientos intensos, zapateado, palmas y expresión emocional profunda. Es una forma de arte declarada Patrimonio Cultural Inmaterial de la Humanidad por la UNESCO.</p>
      <img src="media/flamenco.jpg" alt="Baile Flamenco" width="400">
    </section>

    <section>
      <h2>Horarios y Precios</h2>
      <table>
        <tr>
          <th>Día</th>
          <th>Horario</th>
          <th>Nivel</th>
          <th>Precio mensual</th>
        </tr>
        <tr>
          <td>Lunes y Miércoles</td>
          <td>6:00 PM - 7:00 PM</td>
          <td>Principiantes</td>
          <td>$350</td>
        </tr>
        <tr>
          <td>Martes y Jueves</td>
          <td>7:00 PM - 8:30 PM</td>
          <td>Avanzados</td>
          <td>$400</td>
        </tr>
      </table>
    </section>

    <section>
      <h2>Inscríbete a Flamenco</h2>
      <form>
        <label>Nombre completo: <input type="text" name="nombre"></label><br>
        <label>Edad: <input type="number" name="edad"></label><br>
        <label>Email: <input type="email" name="email"></label><br>
        <label>Selecciona tu nivel:
          <select>
            <option>Principiantes</option>
            <option>Avanzados</option>
          </select>
        </label><br>
        <input type="submit" value="Inscribirme">
      </form>
    </section>

    <section>
      <h2>Video de clase</h2>
      <video src="media/flamenco-video.mp4" width="400" controls></video>
    </section>

    <section>
      <h2>Música típica del Flamenco</h2>
      <audio src="media/flamenco-musica.mp3" controls></audio>
    </section>
  </main>

  <footer>
    <marquee>¡Ven y vive la pasión del Flamenco con nosotros!</marquee>
    <p>&copy; 2025 Academia Estrella</p>
  </footer>
</body>
</html>
