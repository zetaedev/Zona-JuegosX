# Zona-JuegosX
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>ZonaJuegoX</title>
    <style>
        body {
            margin: 0;
            background-color: #111;
            color: #eee;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            padding: 20px;
            text-align: center;
        }

        header {
            font-size: 4rem;
            font-weight: 900;
            color: #0f0;
            margin-bottom: 20px;
            text-shadow: 0 0 10px #0f0;
        }

        p.description {
            font-size: 1.5rem;
            max-width: 600px;
            margin: 0 auto 40px;
            line-height: 1.6;
            color: #ccc;
            text-shadow: 0 0 5px #000;
        }

        .juego {
            max-width: 700px;
            margin: 0 auto 40px;
            background-color: #222;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px #0f0a;
        }

            .juego h2 {
                color: #0f0;
                margin-bottom: 10px;
            }

            .juego p {
                font-size: 1.2rem;
                color: #ddd;
            }

        .descargar {
            margin-top: 20px;
        }

            .descargar a {
                display: inline-block;
                background-color: #0f0;
                color: #000;
                padding: 12px 30px;
                font-weight: bold;
                border-radius: 5px;
                text-decoration: none;
                font-size: 1.1rem;
                box-shadow: 0 0 8px #0f0;
                transition: background-color 0.3s ease;
            }

                .descargar a:hover {
                    background-color: #0c0;
                }

        iframe {
            width: 100%;
            height: 360px;
            border: none;
            border-radius: 10px;
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <header>ZonaJuegoX</header>

    <p class="description">
        ¡Bienvenido a ZonaJuegoX!
        La mejor página para descargar tus juegos favoritos por MEDIAFIRE,
        rápido, seguro y sin complicaciones.
        Descubrí los títulos más buscados, versiones listas para jugar,
        y todo en un solo lugar para que disfrutes al máximo.
    </p>

    <div class="juego">
        <h2>Counter Strike 1.6</h2>
        <p>
            El clásico juego de disparos en primera persona que revolucionó el mundo gamer.
            Disfrutá partidas rápidas y emocionantes, con mapas icónicos y acción sin parar.
            Versión lista para descargar y jugar, comprimida en un archivo ZIP para fácil instalación.
        </p>

        <p>🎬 Mira el video para desbloquear la descarga:</p>

        <!-- Video placeholder: poné el video que quieras acá -->
        <iframe id="video" src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>

        <!-- Botón de descarga oculto inicialmente -->
        <div class="descargar" id="descarga-cs16" style="display:none;">
            <a href="https://www.mediafire.com/file/bski2j58328ivgk/COUNTER-STRIKE+1.6.zip/file" target="_blank" rel="noopener noreferrer">
                Descargar Counter Strike 1.6
            </a>
        </div>
    </div>

    <script>
    // Mostrar el botón después de 30 segundos (simulando que vieron el video)
    setTimeout(() => {
      document.getElementById('descarga-cs16').style.display = 'block';
    }, 30000);
    </script>
</body>
</html>
