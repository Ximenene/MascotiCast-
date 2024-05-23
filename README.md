rodriguez anaya ximena yamile
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <h2>Mascoticas</h2>
  <meta name="description" content="Presentamos historias conmovedoras de rescates, testimonios de dueños de mascotas, galerías de fotos y videos adorables, así como foros o espacios para que la comunidad comparta experiencias y consejos. Mascoticas es un lugar donde los amantes de los animales pueden encontrar información útil y disfrutar del amor por sus mascotas.">
  <meta name="keywords" content="mascotas, gatos, perros, adopción, cuidado de animales">
  <meta name="author" content="Xime">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Mascoticas</h1>
    <nav aria-label="Barra de navegación">
      <ul>
        <li><a href="#misionVisionValores">Misión, Visión y Valores</a></li>
        <li><a href="#catalogo">Catálogo de Mascotas</a></li>
        <li><a href="#historiasRescate">Historias de Rescate</a></li>
        <li><a href="#foro">Foro</a></li>
        <li><a href="#formularioContacto">Contáctanos</a></li>
        <li><a href="#mapaLocalizacion">Encuéntranos</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="misionVisionValores">
      <h2>Misión, Visión y Valores</h2>
      <article>
        <h3>Misión</h3>
        <p>Proporcionar a nuestros clientes la mejor experiencia en cuidar animales, especialmente si fueron maltratados.</p>
        <h3>Valores</h3>
        <p>Cariño, autenticidad, cuidado y satisfacción del cliente.</p>
      </article>
    </section>
</main>
<main>
    <section id="catalogo">
      <h2>Catálogo de Mascotas</h2>
      <ul aria-label="Lista de mascotas disponibles para adopción">
        <li>Gato - Tom</li>
        <li>Pato - Daisy</li>
        <li>Gato - Luna</li>
        <li>Perro - Rocky</li>
        <li>Gato - Simba</li>
        <li>Perro - Charlie</li>
      </ul>
    </section>
</main>

<main>
    <section id="historiasRescate">
      <h2>Historias de Rescate</h2>
      <article>
        <h3>Tom</h3>
        <p>Tom fue rescatado de las calles y ahora disfruta de una vida plena en su nuevo hogar.</p>
        <h3>Max</h3>
        <p>Max fue encontrado herido, pero después de mucho amor y cuidado, se ha recuperado completamente.</p>
      </article>
    </section>
</main>

<main>
    <section id="foro">
      <h2>Foro</h2>
      <p>Únete a nuestra comunidad para compartir experiencias y consejos sobre el cuidado de mascotas.</p>
      <a href="foro.html">Visita nuestro foro</a>
    </section>
</main>

<main>
    <section id="formularioContacto">
      <h2>Contáctanos</h2>
      <form aria-label="Formulario de contacto">
        <label for="nombre">Nombre:</label><br>
        <input type="text" id="nombre" name="nombre" required><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br>
        <label for="mensaje">Mensaje:</label><br>
        <textarea id="mensaje" name="mensaje" rows="4" cols="50" required></textarea><br>
        <input type="submit" value="Enviar">
      </form>
    </section>
</main>

<main>
    <section id="mapaLocalizacion">
      <h2>Encuéntranos</h2>
      <figure aria-label="Mapa de la ubicación">
        <img src="mapa.jpg" alt="Mapa de la ubicación">
        <figcaption>Mapa de la ubicación de Mascoticas.</figcaption>
      </figure>
    </section>
  </main>
</body>
</html>
