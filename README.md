<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Ejemplo con HTML y Bootstrap</title>
  <!-- Bootstrap 5 CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Header -->
  <header class="bg-primary text-white text-center py-4">
    <h1>Mi Página Web</h1>
    <p>Ejemplo usando HTML y Bootstrap</p>
  </header>

  <!-- Nav -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Inicio</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Inicio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Servicios</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contacto</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Main -->
  <main class="container my-5">
    <div class="row">
      <div class="col-md-8">
        <h2>Bienvenido</h2>
        <p>Este es el contenido principal de la página. Aquí puedes colocar texto, imágenes, enlaces, etc.</p>
      </div>
      <div class="col-md-4">
        <h3>Barra lateral</h3>
        <p>Este espacio puede usarse para información adicional, enlaces o widgets.</p>
      </div>
    </div>
  </main>

  <!-- Footer -->
  <footer class="bg-secondary text-white text-center py-3">
    <p>&copy; 2025 Mi Página Web - Todos los derechos reservados</p>
  </footer>

  <!-- Bootstrap JS (opcional para componentes interactivos como el menú móvil) -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
