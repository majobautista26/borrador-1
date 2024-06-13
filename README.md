permalink: /404.html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>María José Piña Bautista - Marketing Digital</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #3a3a3c;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #494949;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #333;
        }
        section {
            padding: 20px;
        }
        .content {
            max-width: 800px;
            margin: auto;
        }
        h2 {
            color: #3a3a3c;
        }
        .skills, .experience, .education {
            margin-bottom: 20px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form label {
            margin-bottom: 5px;
        }
        .contact-form input, .contact-form textarea {
            margin-bottom: 10px;
            padding: 10px;
            font-size: 16px;
        }
        .contact-form input[type="submit"] {
            background-color: #3a3a3c;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        .contact-form input[type="submit"]:hover {
            background-color: #494949;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #3a3a3c;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>María José Piña Bautista</h1>
        <p>Marketing Digital</p>
    </header>
    <nav>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#habilidades">Habilidades</a>
        <a href="#experiencia">Experiencia</a>
        <a href="#educacion">Educación</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="sobre-mi">
        <div class="content">
            <h2>Sobre mí</h2>
            <p>Hola, soy María José Piña Bautista, una apasionada del marketing digital con experiencia en estrategias de marketing, SEO, y gestión de redes sociales. Me encanta ayudar a las empresas a crecer y alcanzar sus objetivos a través de campañas de marketing efectivas.</p>
        </div>
    </section>
    <section id="habilidades">
        <div class="content">
            <h2>Habilidades</h2>
            <ul>
                <li>Marketing Digital</li>
                <li>SEO</li>
                <li>Gestión de Redes Sociales</li>
                <li>Google Analytics</li>
                <li>Publicidad en línea</li>
                <li>Creación de Contenidos</li>
            </ul>
        </div>
    </section>
    <section id="experiencia">
        <div class="content">
            <h2>Experiencia</h2>
            <p>Aquí puedes incluir tu experiencia laboral detallada, con las empresas en las que has trabajado y tus logros principales.</p>
        </div>
    </section>
    <section id="educacion">
        <div class="content">
            <h2>Educación</h2>
            <p>Aquí puedes incluir tu formación académica, como los títulos obtenidos y las instituciones donde estudiaste.</p>
        </div>
    </section>
    <section id="contacto">
        <div class="content">
            <h2>Contacto</h2>
            <form class="contact-form">
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Correo electrónico:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Mensaje:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                <input type="submit" value="Enviar">
            </form>
        </div>
    </section>
    <footer>
        &copy; 2024 María José Piña Bautista
    </footer>
</body>
</html>
