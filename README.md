<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web Moderna</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* Estilos generales */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f4f6;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #4e8cff, #1c5eff);
            color: white;
            padding: 20px 10px;
            text-align: center;
            border-radius: 0 0 30px 30px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 10px 0 0;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.1rem;
            padding: 10px 15px;
            border-radius: 20px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: rgba(255, 255, 255, 0.2);
        }

        main {
            padding: 20px;
        }

        section {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            margin-top: 0;
        }

        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .thumbnail {
            position: relative;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .thumbnail img {
            width: 100%;
            height: auto;
        }

        .thumbnail .title {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 10px;
            font-size: 1rem;
        }

        ul {
            padding-left: 20px;
        }

        ul li {
            margin: 10px 0;
        }

        ul li a {
            text-decoration: none;
            color: #1c5eff;
            font-weight: bold;
        }

        ul li a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            background: #4e8cff;
            color: white;
            padding: 10px 0;
            margin-top: 20px;
            border-radius: 30px 30px 0 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Página Web Moderna</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#videos">Videos</a></li>
                <li><a href="#programas">Programas</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="inicio">
            <h2>Bienvenido a Mi Canal</h2>
            <p>En este sitio encontrarás información sobre mi canal de YouTube, una colección de videos educativos y herramientas que utilizo en mis proyectos de ingeniería electrónica.</p>
        </section>

        <section id="videos">
            <h2>Mis Videos</h2>
            <div class="grid-container">
                <div class="thumbnail">
                    <a href="https://www.youtube.com/embed/TU_VIDEO_ID" target="_blank">
                        <img src="miniatura1.jpg" alt="Miniatura Video 1">
                        <div class="title">Título del Video 1</div>
                    </a>
                </div>
                <div class="thumbnail">
                    <a href="https://www.youtube.com/embed/OTRO_VIDEO_ID" target="_blank">
                        <img src="miniatura2.jpg" alt="Miniatura Video 2">
                        <div class="title">Título del Video 2</div>
                    </a>
                </div>
            </div>
        </section>

        <section id="programas">
            <h2>Programas que Utilizo</h2>
            <ul>
                <li><a href="#programa1">Programa 1</a></li>
                <li><a href="#programa2">Programa 2</a></li>
            </ul>

            <article id="programa1">
                <h3>Programa 1</h3>
                <p>Descripción del programa 1. Este programa es utilizado para tareas específicas en proyectos de electrónica.</p>
                <a href="ENLACE_PROGRAMA1" download>Descargar Programa 1</a>
            </article>

            <article id="programa2">
                <h3>Programa 2</h3>
                <p>Descripción del programa 2. Este programa es útil para análisis y simulaciones.</p>
                <a href="ENLACE_PROGRAMA2" download>Descargar Programa 2</a>
            </article>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Mi Canal de YouTube</p>
    </footer>
</body>
</html>
