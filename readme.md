<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Galería XXX | Solo para Adultos</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Verificación de edad (popup simple al cargar) -->
    <div id="age-check" class="modal">
        <div class="modal-content">
            <h2>Acceso solo para adultos</h2>
            <p>Debes tener 18 años o más para entrar. ¿Eres mayor de edad?</p>
            <button onclick="enterSite()">Sí, tengo +18</button>
            <button onclick="window.location.href='https://www.google.com'">No</button>
        </div>
    </div>

    <header>
        <h1>Galería Sexual XXX</h1>
        <nav>
            <a href="#fotos">Fotos</a>
            <a href="#videos">Videos</a>
        </nav>
    </header>

    <section id="fotos">
        <h2>Fotos XXX</h2>
        <div class="gallery">
            <!-- Sustituye por tus imágenes reales -->
            <img src="assets/foto1.jpg" alt="Foto sexual 1">
            <img src="assets/foto2.jpg" alt="Foto sexual 2">
        </div>
    </section>

    <section id="videos">
        <h2>Videos XXX</h2>
        <div class="gallery">
            <!-- Ejemplo de videos locales -->
            <video controls>
                <source src="assets/video1.mp4" type="video/mp4">
                Tu navegador no soporta el video.
            </video>
            <video controls>
                <source src="assets/video2.mp4" type="video/mp4">
            </video>
        </div>
    </section>

    <footer>
        <p>Aviso Legal: Solo para mayores de edad (+18). Todo el contenido presente cumple con la normativa vigente.</p>
    </footer>

    <script>
        function enterSite() {
            document.getElementById('age-check').style.display = 'none';
        }
        window.onload = function() {
            document.getElementById('age-check').style.display = 'flex';
        }
    </script>
</body>
</html> 
