<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Epic - Catálogo</title>
    <style>
        /* Estilos generales */
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
        }

        /* Encabezado */
        header {
            text-align: center;
            margin-bottom: 30px;
        }
        header h1 {
            color: #e50914; /* Rojo tipo Netflix */
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        header p {
            color: #aaaaaa;
            font-size: 1.1em;
        }

        /* Barra de búsqueda */
        .search-container {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }
        .search-container input {
            width: 80%;
            max-width: 500px;
            padding: 12px 20px;
            border-radius: 25px;
            border: none;
            background-color: #2a2a2a;
            color: white;
            font-size: 16px;
            outline: none;
        }

        /* Botones de filtro */
        .filters {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }
        .filters button {
            background-color: #2a2a2a;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 20px;
            cursor: pointer;
            font-weight: bold;
            transition: 0.3s;
        }
        .filters button.active {
            background-color: #e50914;
        }
        .filters button:hover {
            background-color: #444;
        }

        /* Cuadrícula de tarjetas */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }

        /* Tarjeta individual */
        .card {
            background-color: #1e1e1e;
            border-radius: 10px;
            overflow: hidden;
            position: relative;
            transition: transform 0.3s;
        }
        .card:hover {
            transform: scale(1.05);
        }
        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            display: block;
        }
        .card-info {
            padding: 10px;
            text-align: center;
        }
        .card-info h3 {
            margin: 5px 0;
            font-size: 1em;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }
        .card-info p {
            margin: 0;
            color: #888;
            font-size: 0.85em;
        }
        
        /* Botón de WhatsApp en la tarjeta */
        .btn-wa {
            display: block;
            background-color: #25D366;
            color: white;
            text-align: center;
            padding: 8px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            margin-top: 10px;
            font-size: 0.9em;
        }
        .btn-wa:hover {
            background-color: #1ebd5a;
        }

        /* Información de contacto al final */
        .contacto {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            background-color: #1e1e1e;
            border-radius: 10px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        .contacto h2 { color: #e50914; }
        .contacto p { margin: 5px 0; color: #ccc; }
    </style>
</head>
<body>

    <header>
        <h1>Epic</h1>
        <p>Grabamos lo que necesites: solo pide tu serie o película favorita.</p>
    </header>

    <div class="search-container">
        <input type="text" id="buscador" placeholder="Buscar series, películas o anime..." onkeyup="filtrar()">
    </div>

    <div class="filters">
        <button class="active" onclick="filtrarCategoria('todos', this)">Todos</button>
        <button onclick="filtrarCategoria('pelicula', this)">Películas</button>
        <button onclick="filtrarCategoria('anime', this)">Anime</button>
        <button onclick="filtrarCategoria('serie', this)">Series</button>
    </div>

    <div class="grid" id="catalogo">
        
        <!-- TARJETA 1 (Ejemplo Película) -->
        <div class="card" data-categoria="pelicula" data-titulo="300">
            <!-- Para cambiar la imagen, sube tu foto a github y pon el enlace aquí -->
            <img src="https://image.tmdb.org/t/p/w500/a0nM2b3m2Yk.jpg" alt="300">
            <div class="card-info">
                <h3>300</h3>
                <p>Película - 30 pesos</p>
                <a href="https://wa.me/5356439106?text=Hola,%20quiero%20la%20pelicula%20300" class="btn-wa" target="_blank">Pedir por WhatsApp</a>
            </div>
        </div>

        <!-- TARJETA 2 (Ejemplo Anime) -->
        <div class="card" data-categoria="anime" data-titulo="Naruto">
            <img src="https://image.tmdb.org/t/p/w500/xS3m2b3m2Yk.jpg" alt="Naruto">
            <div class="card-info">
                <h3>Naruto Shippuden</h3>
                <p>Anime (Cap) - 10 pesos</p>
                <a href="https://wa.me/5356439106?text=Hola,%20quiero%20el%20anime%20Naruto" class="btn-wa" target="_blank">Pedir por WhatsApp</a>
            </div>
        </div>

        <!-- TARJETA 3 (Ejemplo Película Anime) -->
        <div class="card" data-categoria="anime" data-titulo="Your Name">
            <img src="https://image.tmdb.org/t/p/w500/q719jXXEzOoYaps6babgKnONONX.jpg" alt="Your Name">
            <div class="card-info">
                <h3>Your Name</h3>
                <p>Película Anime - 30 pesos</p>
                <a href="https://wa.me/5356439106?text=Hola,%20quiero%20la%20pelicula%20Your%20Name" class="btn-wa" target="_blank">Pedir por WhatsApp</a>
            </div>
        </div>

        <!-- TARJETA 4 (Ejemplo Serie) -->
        <div class="card" data-categoria="serie" data-titulo="Breaking Bad">
            <img src="https://image.tmdb.org/t/p/w500/ggFHVbOOe6L4Q5z9rPqQ7Z9Y2.jpg" alt="Breaking Bad">
            <div class="card-info">
                <h3>Breaking Bad</h3>
                <p>Serie - 15 pesos</p>
                <a href="https://wa.me/5356439106?text=Hola,%20quiero%20la%20serie%20Breaking%20Bad" class="btn-wa" target="_blank">Pedir por WhatsApp</a>
            </div>
        </div>

        <!-- TARJETA 5 (Ejemplo Película HD) -->
        <div class="card" data-categoria="pelicula" data-titulo="Dune 2">
            <img src="https://image.tmdb.org/t/p/w500/1pdfLvkbY9ohJlCjQH2CZjjYVvJ.jpg" alt="Dune 2">
            <div class="card-info">
                <h3>Dune: Parte 2</h3>
                <p>Película HD - 50 pesos</p>
                <a href="https://wa.me/5356439106?text=Hola,%20quiero%20la%20pelicula%20Dune%202" class="btn-wa" target="_blank">Pedir por WhatsApp</a>
            </div>
        </div>

        <!-- TARJETA 6 (Ejemplo Anime) -->
        <div class="card" data-categoria="anime" data-titulo="Jujutsu Kaisen">
            <img src="https://image.tmdb.org/t/p/w500/fHpKWq9ayzSk8nSwqRuaAUemRKh.jpg" alt="Jujutsu Kaisen">
            <div class="card-info">
                <h3>Jujutsu Kaisen</h3>
                <p>Anime (Cap) - 10 pesos</p>
                <a href="https://wa.me/5356439106?text=Hola,%20quiero%20el%20anime%20Jujutsu%20Kaisen" class="btn-wa" target="_blank">Pedir por WhatsApp</a>
            </div>
        </div>

    </div>

    <div class="contacto">
        <h2>Información de Contacto</h2>
        <p><strong>Dirección:</strong> Calle Máximo Gómez entre Marina y Sayas #103, en Alto.</p>
        <p><strong>Horario:</strong> Todos los días de 8:30 a.m. a 8:00 p.m.</p>
        <p><strong>Teléfono:</strong> 56439106</p>
    </div>

    <script>
        let categoriaActual = 'todos';

        // Función para los botones de categoría
        function filtrarCategoria(categoria, btn) {
            categoriaActual = categoria;
            
            // Quitar la clase 'active' de todos los botones
            document.querySelectorAll('.filters button').forEach(b => b.classList.remove('active'));
            // Ponerla en el botón clickeado
            btn.classList.add('active');
            
            filtrar(); // Ejecutar el filtro general
        }

        // Función que filtra por texto y por categoría
        function filtrar() {
            const texto = document.getElementById('buscador').value.toLowerCase();
            const tarjetas = document.querySelectorAll('.card');

            tarjetas.forEach(tarjeta => {
                const titulo = tarjeta.getAttribute('data-titulo').toLowerCase();
                const categoria = tarjeta.getAttribute('data-categoria');
                
                // Verifica si coincide con el texto de búsqueda
                const coincideTexto = titulo.includes(texto);
                // Verifica si coincide con la categoría
                const coincideCategoria = (categoriaActual === 'todos' || categoriaActual === categoria);

                if (coincideTexto && coincideCategoria) {
                    tarjeta.style.display = 'block';
                } else {
                    tarjeta.style.display = 'none';
                }
            });
        }
    </script>
</body>
</html>