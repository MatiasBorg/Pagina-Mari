<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de la Diseñadora Industrial</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-size: 1.2em;
            margin: 5px 0 20px;
        }
        section {
            padding: 20px;
            margin: 10px;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
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
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }
        .portfolio-item:hover {
            transform: scale(1.05);
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background: #333;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin: 10px 0 5px;
        }
        input[type="text"],
        input[type="email"],
        textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        input[type="submit"] {
            background-color: #333;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        input[type="submit"]:hover {
            background-color: #555;
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
        <div class="portfolio-item">
            <h3>Proyecto 1</h3>
            <img src="URL_DE_TU_IMAGEN_1" alt="Descripción del Proyecto 1" style="width:100%; border-radius: 5px;">
            <p>Descripción breve del proyecto 1.</p>
        </div>
        <div class="portfolio-item">
            <h3>Proyecto 2</h3>
            <img src="URL_DE_TU_IMAGEN_2" alt="Descripción del Proyecto 2" style="width:100%; border-radius: 5px;">
            <p>Descripción breve del proyecto 2.</p>
        </div>
        <div class="portfolio-item">
            <h3>Proyecto 3</h3>
            <img src="URL_DE_TU_IMAGEN_3" alt="Descripción del Proyecto 3" style="width:100%; border-radius: 5px;">
            <p>Descripción breve del proyecto 3.</p>
        </div>
    </div>
</section>

<section>
    <h2>Contacto</h2>
    <form>
        <label for="name">Nombre:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Correo electrónico:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Mensaje:</label>
        <textarea id="message" name="message" required></textarea>
        
        <input type="submit" value="Enviar">
    </form>
</section>

<footer>
    <p>&copy; 2024 Diseñadora Industrial. Todos los derechos reservados.</p>
</footer>

</body>
</html>
