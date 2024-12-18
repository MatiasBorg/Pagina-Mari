<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de la Diseñadora Industrial</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        section {
            padding: 20px;
            margin: 10px;
            background: #fff;
            border-radius: 5px;
        }
        .portfolio {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .portfolio-item {
            margin: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 10px;
            width: 30%;
            transition: transform 0.2s;
        }
        .portfolio-item:hover {
            transform: scale(1.05);
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #333;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Diseñadora Industrial</h1>
    <p>Bienvenida a mi portafolio</p>
</header>

<section>
    <h2>Sobre mí</h2>
    <p>Soy una diseñadora industrial apasionada por crear soluciones innovadoras y funcionales. Mi enfoque está en la sostenibilidad y la estética.</p>
</section>

<section>
    <h2>Portafolio</h2>
    <div class="portfolio">
        <a href="https://github.com/MatiasBorg/PaginaMari/blob/main/Portada-Diseno-Industrial-Blog-2.png" class="portfolio-item">
            <h3>Proyecto 1</h3>
            <p>Descripción breve del proyecto 1.</p>
        </a>
        <a href="proyecto2.html" class="portfolio-item">
            <h3>Proyecto 2</h3>
            <p>Descripción breve del proyecto 2.</p>
        </a>
        <a href="proyecto3.html" class="portfolio-item">
            <h3>Proyecto 3</h3>
            <p>Descripción breve del proyecto 3.</p>
        </a>
    </div>
</section>

<section>
    <h2>Contacto</h2>
    <form>
        <label for="name">Nombre:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Correo electrónico:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Mensaje:</label><br>
        <textarea id="message" name="message" required></textarea><br><br>
        <input type="submit" value="Enviar">
    </form>
</section>

<footer>
    <p>&copy; 2024 Diseñadora Industrial. Todos los derechos reservados.</p>
</footer>

</body>
</html>
