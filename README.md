<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Un blog moderno basato sulla geometria sacra e le proporzioni auree.">
    <title>Il Mio Blog</title>
    <style>
        /* Stili di base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f3f4f6;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            font-size: 2em;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: center;
            padding: 15px;
            background-color: #444;
            position: fixed;
            width: 100%;
            top: 80px;
            left: 0;
            z-index: 999;
        }

        nav a {
            color: #fff;
            margin: 0 20px;
            text-decoration: none;
            font-size: 1.2em;
        }

        nav a:hover {
            color: #f0c674;
        }

        section {
            padding: 100px 20px 50px;
            min-height: 100vh;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        h1, h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Stili proporzione aurea */
        .golden-ratio {
            display: grid;
            grid-template-columns: 1fr 1.618fr;
            gap: 20px;
        }

        .golden-ratio img {
            width: 100%;
            height: auto;
        }

        /* Sezione Home */
        .home {
            background-image: url('https://example.com/geometria-sacra-home.jpg');
            background-size: cover;
            background-position: center;
            color: #fff;
        }

        .home h1 {
            font-size: 3em;
        }

        /* Sezione Chi sono */
        .about {
            background-color: #f5f5f5;
            padding: 50px 20px;
        }

        .about h2 {
            font-size: 2.5em;
        }

        .about p {
            font-size: 1.2em;
            line-height: 1.6;
        }

        /* Sezione Servizi */
        .services {
            background-color: #fff;
        }

        .service {
            padding: 20px;
            border: 1px solid #ccc;
            margin-bottom: 20px;
            text-align: center;
        }

        /* Sezione Contatti */
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact-form button {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #f0c674;
        }

        /* Sezione Galleria */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .gallery img {
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

    <header>
        Il Mio Blog
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">Chi sono</a>
        <a href="#services">Servizi</a>
        <a href="#contact">Contatti</a>
        <a href="#gallery">Galleria</a>
    </nav>

    <!-- Sezione Home -->
    <section id="home" class="home container">
        <h1>Benvenuti nel Mio Blog</h1>
        <p>Un viaggio nella geometria sacra e le proporzioni auree.</p>
    </section>

    <!-- Sezione Chi sono -->
    <section id="about" class="about container">
        <h2>Chi Sono</h2>
        <div class="golden-ratio">
            <img src="https://example.com/geometria-sacra.jpg" alt="Geometria sacra">
            <p>Sono un appassionato di geometria sacra e filosofia delle proporzioni auree. Attraverso questo blog, esploro i legami tra arte, natura e matematica, con l’obiettivo di condividerne la bellezza con il mondo.</p>
        </div>
    </section>

    <!-- Sezione Servizi -->
    <section id="services" class="services container">
        <h2>Servizi</h2>
        <div class="golden-ratio">
            <div class="service">
                <h3>Consulenza sulla Geometria Sacra</h3>
                <p>Offro consulenze per artisti, architetti e designer per integrare i principi della geometria sacra nelle loro creazioni.</p>
            </div>
            <div class="service">
                <h3>Workshop di Proporzione Aurea</h3>
                <p>Partecipa ai miei workshop per apprendere come usare le proporzioni auree in vari ambiti, dall'arte all'architettura.</p>
            </div>
        </div>
    </section>

    <!-- Sezione Contatti -->
    <section id="contact" class="container">
        <h2>Contatti</h2>
        <div class="contact-form">
            <input type="text" placeholder="Nome" required>
            <input type="email" placeholder="Email" required>
            <textarea placeholder="Il tuo messaggio" required></textarea>
            <button type="submit">Invia</button>
        </div>
    </section>

    <!-- Sezione Galleria -->
    <section id="gallery" class="gallery container">
        <h2>Galleria</h2>
        <img src="https://example.com/immagine1.jpg" alt="Geometria Sacra 1">
        <img src="https://example.com/immagine2.jpg" alt="Geometria Sacra 2">
        <img src="https://example.com/immagine3.jpg" alt="Geometria Sacra 3">
    </section>

    <footer>
        <p>&copy; 2024 Il Mio Blog. Tutti i diritti riservati.</p>
    </footer>

</body>
</html>
