<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Sergio Ceballos -- 7-715-876">
    <meta name="description" content="MiTube: página de reproducción de video">
    <title>Cómo construir una página HTML5 desde cero - MiTube</title>
    
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <a href="#">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTeAwVo_85w0AnQQlYJ2zCTNR6bNCE0L1MzyCvB3qZr-cruWESTW5KG4baO&s=10" alt="Logo de MiTube" width="120">
        </a>
        <form action="#" role="search">
            <input type="search" name="q" placeholder="Buscar" required>
            
            <button type="submit" class="btn">Buscar</button>
        </form>

        <nav class="navbar">
            <ul>
                
                <li><a href="#" class="nav-link">Inicio</a></li>
                <li><a href="#" class="nav-link">Suscripciones</a></li>
                <li><a href="#" class="nav-link">Explorar</a></li>
            </ul>
        </nav>
    </header>

    <main>
        
        <section id="video-player">
            <iframe width="640" height="360"
                src="https://www.youtube.com/embed/ls-DIlURr8Y?si=2iNGUGLKu9Pdmxws"
                title="Cómo construir una página HTML5 desde cero"
                allowfullscreen></iframe>

            <h1>Cómo construir una página HTML5 desde cero</h1>

            <p>
                <span>15,342 vistas</span> ·
                <time datetime="2026-08-20">20 de agosto de 2026</time>
            </p>

            <div>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQddRWSF2aGyXbfm9C7_wesTFQx4mCzbXLjDGYTXk6kiqbKgIjTi9wGH2I&s=10" alt="Avatar del canal" width="48">
                <p>MiTube Academy</p>
                <!-- Clase btn agregada al botón Suscribirse[cite: 1] -->
                <button type="button" class="btn">Suscribirse</button>
            </div>

            <p>
                En este video aprenderás a construir la estructura completa de una
                página HTML5 semántica, paso a paso, incluyendo encabezado,
                reproductor de video, comentarios y panel de sugeridos.
                Ideal para quienes están reforzando los conceptos base del curso.
            </p>
        </section>

        <section>
            <h2>Comentarios</h2>

            <form id="form-comentario" action="#">
                <label for="comentario">Agregar un comentario</label>
                <textarea id="comentario" name="comentario" rows="3"
                    placeholder="Agrega un comentario público..." required></textarea>
                <!-- Clase btn agregada al botón de submit de los comentarios[cite: 1] -->
                <button type="submit" class="btn">Comentar</button>
            </form>

            <article>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTEgeWOxcHriPPhOBWwp7nHPMCNM0JPQKb6fAVVAzYfw9jPn64RE9SQhDHq&s=10" alt="Avatar de Laura Gómez" width="40">
                <span>CentralSOC2.0</span>
                <time datetime="2026-08-21">21 de agosto de 2026</time>
                <p>Excelente explicación, me quedó muy clara la diferencia entre section y article.</p>
            </article>

            <article>
                <img src="https://i.pinimg.com/736x/6f/83/14/6f8314df3a9248aec1649b49dd752741.jpg" alt="Avatar de Carlos Pérez" width="40">
                <span>Adrian Quintero</span>
                <time datetime="2026-08-21">21 de agosto de 2026</time>
                <p>¿El aside siempre debe ir fuera del main? Justo tenía esa duda.</p>
            </article>

            <article>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSP_B8hDTYypaMT1tBRw-6TGrhMYeoKTJYNMJmM5s8lXt7eg3f21mIV5Igz&s=10" alt="Avatar de Ana Rodríguez" width="40">
                <span>Tung Tung TripleT 67</span>
                <time datetime="2026-08-22">22 de agosto de 2026</time>
                <p>Muy útil el laboratorio, lo usé para repasar antes del examen.</p>
            </article>
        </section>
    </main>

   
    <aside id="sugeridos">
        <h2>Videos sugeridos</h2>

        
        <article class="card">
            <a href="#">
                <img src="https://picsum.photos/id/20/168/94" alt="Miniatura del video: Introducción a CSS3" width="168">
                <h3>Introducción a CSS3</h3>
            </a>
            <p>MiTube Academy</p>
        </article>

        
        <article class="card">
            <a href="#">
                <img src="https://picsum.photos/id/28/168/94" alt="Miniatura del video: Formularios HTML avanzados" width="168">
                <h3>Formularios HTML avanzados</h3>
            </a>
            <p>MiTube Academy</p>
        </article>

        
        <article class="card">
            <a href="#">
                <img src="https://picsum.photos/id/36/168/94" alt="Miniatura del video: Semántica HTML5 explicada" width="168">
                <h3>Semántica HTML5 explicada</h3>
            </a>
            <p>MiTube Academy</p>
        </article>

        
        <article class="card">
            <a href="#">
                <img src="https://picsum.photos/id/48/168/94" alt="Miniatura del video: Buenas prácticas de accesibilidad" width="168">
                <h3>Buenas prácticas de accesibilidad</h3>
            </a>
            <p>MiTube Academy</p>
        </article>
    </aside>

    
    <footer id="pie">
        <ul>
            <li><a href="#">Acerca de</a></li>
            <li><a href="#">Prensa</a></li>
            <li><a href="#">Copyright</a></li>
            <li><a href="#">Términos</a></li>
            <li><a href="#">Privacidad</a></li>
        </ul>
        <p>&copy; 2026 MiTube</p>
    </footer>
</body>
</html>


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: Arial, sans-serif;
    color: #212121;
    background-color: #f9f9f9;
    line-height: 1.5;
}


header {
    display: flex;
    align-items: center;
    gap: 24px;
    background-color: #ffffff;
    padding: 10px 24px;
    border-bottom: 1px solid #e5e5e5;
    position: sticky;
    top: 0;
    z-index: 10;
}


header > a:first-child {
    display: flex;
    align-items: center;
    gap: 6px;
    text-decoration: none;
    flex-shrink: 0;
}

header > a:first-child img {
    width: 32px;
    height: 32px;
    display: block;
}


header > a:first-child::after {
    content: "YutuChafa";
    font-size: 1.4rem;
    font-weight: 700;
    letter-spacing: -0.5px;
    color: #0e4fc1;
    font-family: Arial, sans-serif;
}

/* Barra de búsqueda */
header form[role="search"] {
    display: flex;
    flex: 1;
    max-width: 600px;
}

header form[role="search"] input[type="search"] {
    flex: 1;
    padding: 8px 12px;
    border: 1px solid #020202;
    border-right: none;
    border-radius: 20px 0 0 20px;
    outline: none;
}


.navbar {
    margin-left: auto;
}

.navbar ul {
    display: flex;
    gap: 16px;
    list-style: none;
}


.nav-link {
    color: #1b2a4a;
    text-decoration: none;
    font-weight: bold;
}

.nav-link:hover {
    color: #cc0000;
}


.btn {
    background-color: #5515bd;
    color: #020101;
    border: none;
    padding: 8px 16px;
    border-radius: 4px;
    cursor: pointer;
    font-weight: bold;
}

.btn:hover {
    background-color: #121111;
}


header form[role="search"] .btn {
    border-radius: 0 20px 20px 0;
    padding: 8px 18px;
}


.card {
    margin-bottom: 12px;
    padding: 8px;
    border: 1px solid #dddddd;
    border-radius: 6px;
    background-color: #ffffff;
}

.card a {
    text-decoration: none;
    color: inherit;
}

.card h3 {
    font-size: 0.95rem;
    margin-top: 6px;
}

.card p {
    font-size: 0.85rem;
    color: #606060;
    margin-top: 2px;
}


body > main,
body > aside {
    display: inline-block;
    vertical-align: top;
}

main {
    max-width: calc(100% - 300px - 24px);
    padding: 16px 24px;
}


#video-player {
    max-width: 720px;
    margin: 24px auto;
}

#video-player iframe {
    width: 100%;
    height: auto;
    aspect-ratio: 16 / 9;
    border: none;
    border-radius: 8px;
}

#video-player > div {
    display: flex;
    align-items: center;
    gap: 12px;
    margin: 12px 0;
}

#video-player > div img {
    width: 48px;
    height: 48px;
    border-radius: 50%;
}

#video-player > div p {
    flex: 1;
    font-weight: bold;
}


#sugeridos {
    width: 300px;
    background-color: #eef1f6;
    padding: 12px;
    vertical-align: top;
}


#pie {
    background-color: #1b2a4a;
    color: #ffffff;
    padding: 16px;
    text-align: center;
}

#pie ul {
    display: flex;
    justify-content: center;
    gap: 16px;
    list-style: none;
    margin-bottom: 8px;
    flex-wrap: wrap;
}

#pie a {
    color: #ffffff;
    text-decoration: none;
    font-size: 0.85rem;
}

#pie a:hover {
    text-decoration: underline;
}


#form-comentario {
    margin: 16px 0;
}

#form-comentario label {
    display: block;
    margin-bottom: 6px;
    font-weight: bold;
}

#form-comentario textarea {
    width: 100%;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
    resize: vertical;
    margin-bottom: 8px;
    font-family: inherit;
}

main section article {
    display: flex;
    gap: 10px;
    margin-bottom: 16px;
}

main section article img {
    border-radius: 50%;
    width: 40px;
    height: 40px;
}

main section article span {
    font-weight: bold;
    margin-right: 8px;
}

main section article time {
    color: #606060;
    font-size: 0.85rem;
}


h1, h2, h3 {
    font-family: Arial, sans-serif;
    color: #1b2a4a;
    margin-bottom: 8px;
}


input[type="search"]:focus,
textarea:focus {
    outline: 2px solid #e8791a;
}


img {
    max-width: 100%;
    height: auto;
    display: block;
}
