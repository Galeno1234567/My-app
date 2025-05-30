<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>💖 Mi Amor Eterno para Rocío Soledad 💖</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;600;700&family=Playfair+Display:ital,wght@0,400;0,600;1,400&display=swap');
        
        body {
            font-family: 'Playfair Display', serif;
            background: linear-gradient(45deg, #FF6B9D, #C44CAE, #8E24AA, #FF8A80);
            background-size: 400% 400%;
            animation: gradientShift 8s ease infinite;
            text-align: center;
            margin: 0;
            padding: 20px;
            color: #4A1A3A;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow-x: hidden;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            max-width: 700px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            padding: 50px;
            border-radius: 30px;
            box-shadow: 0 20px 60px rgba(139, 69, 19, 0.3);
            position: relative;
            overflow: hidden;
            transform: scale(0.9);
            animation: containerEnter 1.5s forwards ease-out;
            border: 3px solid rgba(255, 192, 203, 0.5);
        }

        .container::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255, 182, 193, 0.1) 0%, transparent 70%);
            animation: rotate 20s linear infinite;
            z-index: -1;
        }

        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        @keyframes containerEnter {
            to { transform: scale(1); opacity: 1; }
        }

        h1 {
            font-family: 'Dancing Script', cursive;
            color: #8E24AA;
            margin-bottom: 15px;
            font-size: 42px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
            font-weight: 700;
        }

        .subtitle {
            font-family: 'Dancing Script', cursive;
            font-size: 24px;
            color: #C44CAE;
            margin-bottom: 30px;
            font-style: italic;
        }

        .icon {
            font-size: 60px;
            margin: 20px 0;
            animation: heartBeat 2s infinite ease-in-out;
            display: inline-block;
        }

        @keyframes heartBeat {
            0%, 100% { transform: scale(1); }
            25% { transform: scale(1.1); }
            50% { transform: scale(1.05); }
            75% { transform: scale(1.15); }
        }

        .imagen-amor {
            width: 100%;
            max-width: 520px;
            border-radius: 25px;
            margin: 30px auto;
            border: 8px solid #FFB6C1;
            box-shadow: 0 15px 30px rgba(255, 105, 180, 0.5);
            transition: all 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94);
            filter: brightness(1.05) saturate(1.1);
        }

        .imagen-amor:hover {
            transform: scale(1.05) rotate(2deg);
            box-shadow: 0 20px 40px rgba(255, 105, 180, 0.7);
            filter: brightness(1.1) saturate(1.2);
        }

        .verse {
            background: linear-gradient(135deg, rgba(255, 240, 245, 0.9), rgba(255, 228, 235, 0.9));
            padding: 25px;
            border-radius: 20px;
            margin: 30px 0;
            text-align: left;
            border-left: 8px solid #FF69B4;
            box-shadow: inset 0 0 20px rgba(255, 105, 180, 0.1);
            position: relative;
            overflow: hidden;
        }

        .verse::before {
            content: '❤️';
            position: absolute;
            top: 15px;
            right: 20px;
            font-size: 24px;
            opacity: 0.3;
        }

        .verse h3 {
            color: #8E24AA;
            margin-top: 0;
            font-size: 22px;
            font-family: 'Dancing Script', cursive;
            font-weight: 600;
        }

        .verse p {
            font-size: 18px;
            line-height: 1.7;
            font-style: italic;
        }

        button {
            background: linear-gradient(45deg, #FF6B9D, #8E24AA, #FF1744);
            background-size: 200% 200%;
            animation: buttonGradient 3s ease infinite;
            color: white;
            border: none;
            padding: 20px 40px;
            border-radius: 50px;
            font-size: 22px;
            font-family: 'Dancing Script', cursive;
            font-weight: 600;
            cursor: pointer;
            margin: 40px 0;
            transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
            box-shadow: 0 8px 20px rgba(255, 105, 180, 0.5);
            letter-spacing: 1px;
            position: relative;
            overflow: hidden;
        }

        @keyframes buttonGradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        button:hover {
            transform: translateY(-8px) scale(1.05);
            box-shadow: 0 15px 30px rgba(255, 105, 180, 0.8);
        }

        button::before {
            content: '✨';
            position: absolute;
            top: 50%;
            left: -30px;
            transform: translateY(-50%);
            animation: sparkleMove 2s linear infinite;
        }

        @keyframes sparkleMove {
            0% { left: -30px; opacity: 0; }
            50% { opacity: 1; }
            100% { left: 100%; opacity: 0; }
        }

        #surprise {
            display: none;
            margin-top: 50px;
            animation: surpriseEnter 1.5s forwards ease-out;
        }

        @keyframes surpriseEnter {
            from { opacity: 0; transform: translateY(50px) scale(0.8); }
            to { opacity: 1; transform: translateY(0) scale(1); }
        }

        .love-note {
            font-family: 'Dancing Script', cursive;
            line-height: 2;
            font-size: 22px;
            color: #8E24AA;
            background: linear-gradient(135deg, rgba(255, 240, 245, 0.8), rgba(255, 228, 235, 0.8));
            padding: 35px;
            border-radius: 20px;
            margin: 30px 0;
            box-shadow: 0 10px 25px rgba(255, 105, 180, 0.2);
            position: relative;
            border: 2px solid rgba(255, 182, 193, 0.5);
        }

        .love-note::before {
            content: '💕';
            position: absolute;
            top: -10px;
            left: 20px;
            font-size: 30px;
            background: white;
            padding: 5px;
            border-radius: 50%;
        }

        .love-note strong {
            color: #C44CAE;
            font-weight: 700;
        }

        .romantic-quote {
            font-family: 'Dancing Script', cursive;
            font-size: 28px;
            color: #FF1744;
            background: rgba(255, 255, 255, 0.9);
            padding: 25px;
            border-radius: 15px;
            margin: 25px 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            font-weight: 600;
            position: relative;
        }

        .romantic-quote::before,
        .romantic-quote::after {
            content: '"';
            font-size: 40px;
            color: #FF69B4;
            position: absolute;
        }

        .romantic-quote::before {
            top: 10px;
            left: 15px;
        }

        .romantic-quote::after {
            bottom: 10px;
            right: 15px;
        }

        footer {
            margin-top: 60px;
            font-size: 18px;
            color: #8E24AA;
            font-family: 'Dancing Script', cursive;
            font-weight: 600;
        }

        .floating-hearts {
            position: absolute;
            font-size: 30px;
            animation: floatHeart 8s linear infinite;
            opacity: 0;
            pointer-events: none;
        }

        @keyframes floatHeart {
            0% { transform: translateY(0) rotate(0deg); opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { transform: translateY(-200px) rotate(360deg); opacity: 0; }
        }

        .audio-player {
            background: linear-gradient(135deg, rgba(255, 182, 193, 0.3), rgba(255, 240, 245, 0.6));
            padding: 25px;
            border-radius: 25px;
            margin: 35px 0;
            box-shadow: 0 8px 20px rgba(255, 105, 180, 0.2);
            border: 2px solid rgba(255, 182, 193, 0.4);
        }

        .audio-player p {
            margin-bottom: 15px;
            font-weight: bold;
            color: #8E24AA;
            font-size: 20px;
            font-family: 'Dancing Script', cursive;
        }

        .falling-element {
            position: fixed;
            font-size: 35px;
            animation: fall 6s linear forwards;
            opacity: 0;
            pointer-events: none;
            z-index: 9999;
        }

        @keyframes fall {
            0% { transform: translateY(-50px) rotate(0deg); opacity: 0; }
            20% { opacity: 1; }
            100% { transform: translateY(100vh) rotate(1080deg); opacity: 0; }
        }

        .animated-element {
            opacity: 0;
            transform: translateY(30px);
            animation: fadeInAndSlideUp 1s forwards ease-out;
        }

        @keyframes fadeInAndSlideUp {
            to { opacity: 1; transform: translateY(0); }
        }

        .kiss-animation {
            display: inline-block;
            font-size: 40px;
            animation: kiss 1.5s ease-in-out infinite;
        }

        @keyframes kiss {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.3); }
        }

        .love-poem {
            background: linear-gradient(135deg, rgba(255, 20, 68, 0.1), rgba(142, 36, 170, 0.1));
            padding: 30px;
            border-radius: 20px;
            margin: 30px 0;
            font-family: 'Dancing Script', cursive;
            font-size: 20px;
            line-height: 1.8;
            color: #8E24AA;
            border: 3px solid rgba(255, 105, 180, 0.3);
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="icon">💖</div>
        <h1>Mi Amor Infinito para Rocío Soledad</h1>
        <p class="subtitle">Eres la melodía más hermosa de mi corazón</p>
        
        <img 
            src="https://i.ibb.co/Fqg48tvB/file-00000000eeac52308b735d2d13d6a219-conversation-id-67ebf98d-b0c0-8008-958d-9ba5686ddeb0-message-i.png" 
            alt="El amor de Dios abraza a mi amada Rocío" 
            class="imagen-amor"
        >
        
        <div class="romantic-quote">
            En tus ojos veo el reflejo del cielo, en tu sonrisa encuentro mi hogar
        </div>
        
        <div class="audio-player">
            <p>🎵 Una serenata de amor que susurra tu nombre:</p>
            <audio controls loop>
                <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
                Tu navegador no soporta audio. Puedes escucharla <a href="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" target="_blank">aquí</a>.
            </audio>
            <p style="font-size: 16px; margin-top: 10px; color: #C44CAE;"><i>"Melodía del Corazón" - Dedicada a ti</i></p>
        </div>
        
        <div id="versiculos"></div>
        
        <button onclick="mostrarSorpresa()">💕 Descubre el Secreto de Mi Corazón 💕</button>
        
        <div id="surprise">
            <div class="icon kiss-animation">💋✨💖</div>
            
            <div class="love-poem animated-element" style="animation-delay: 0.3s;">
                <h3 style="color: #FF1744; font-size: 26px; margin-bottom: 20px;">Para Ti, Mi Amada Rocío</h3>
                <p>Eres la estrella que ilumina mis noches oscuras,<br>
                la brisa suave que calma mis tormentas,<br>
                el susurro divino que me recuerda<br>
                que el amor verdadero existe.</p>
                <p>En cada amanecer pienso en tu sonrisa,<br>
                en cada atardecer agradezco tu existencia,<br>
                porque tú, mi querida Rocío,<br>
                eres el regalo más hermoso que Dios me ha dado.</p>
            </div>
            
            <div class="love-note animated-element" style="animation-delay: 0.8s;">
                <p><strong>Mi adorada Rocío</strong>, cuando el cansancio toque tu puerta y la rutina intente apagar tu luz, recuerda que:</p>
                <p><i>«Porque yo sé los planes que tengo para ti –dice el Señor–, planes de bienestar y no de calamidad, a fin de darte un futuro y una esperanza.» (Jeremías 29:11).</i></p>
                <p>Pero más allá de lo que Dios tiene preparado para ti, quiero que sepas que mi corazón late por ti cada segundo, que mis pensamientos vuelan hacia ti como mariposas enamoradas, y que mi amor por ti crece como las flores al recibir el sol de la mañana.</p>
                <p><strong>Eres mi inspiración, mi fortaleza, mi paz, mi todo.</strong> ✨💕</p>
            </div>
            
            <div class="romantic-quote animated-element" style="animation-delay: 1.3s;">
                Si el amor tuviera rostro, tendría el tuyo; si tuviera nombre, sería Rocío
            </div>
            
            <img 
                src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDhyZ2NtN3J6Y3FhY2Vob3R0dGJ5YzN6Y2RlYzB6ZG5mZ2N6eGZ1dSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/X6tL1pI0HX6WI/giphy.gif" 
                alt="Flores danzando de felicidad por nuestro amor"
                class="animated-element"
                style="width: 250px; margin: 30px auto; display: block; animation-delay: 1.8s; border-radius: 20px;"
            >
            
            <div style="position: relative; height: 150px; margin-top: 40px;">
                <div id="hearts-container"></div>
                <p style="margin-top: 80px; font-size: 24px; color: #FF1744; font-weight: bold; font-family: 'Dancing Script', cursive;" class="animated-element" style="animation-delay: 2.3s;">
                    Te amo con un amor que trasciende el tiempo y el espacio ❤️💫
                </p>
            </div>
        </div>
        
        <footer>
            "Eres la poesía que mi alma siempre quiso escribir"<br>
            Con todo mi amor eterno, para la mujer que conquistó mi corazón para siempre.
        </footer>
    </div>

    <script>
        // VERSÍCULOS ROMÁNTICOS Y DE ESPERANZA PARA ROCÍO
        const versiculos = [
            {
                libro: "Cantares 2:10",
                texto: "\"Mi amado habló, y me dijo: Levántate, oh amiga mía, hermosa mía, y ven.\""
            },
            {
                libro: "Mateo 11:28",
                texto: "\"Venid a mí todos los que estáis cansados y agobiados, y yo os haré descansar.\""
            },
            {
                libro: "Cantares 4:7",
                texto: "\"Toda tú eres hermosa, amiga mía, y en ti no hay mancha.\""
            },
            {
                libro: "Isaías 40:31",
                texto: "\"Pero los que esperan en Jehová tendrán nuevas fuerzas; levantarán alas como las águilas.\""
            },
            {
                libro: "1 Corintios 13:8",
                texto: "\"El amor nunca deja de ser; pero las profecías se acabarán, y cesarán las lenguas.\""
            },
            {
                libro: "Proverbios 31:29",
                texto: "\"Muchas mujeres hicieron el bien; mas tú sobrepasas a todas.\""
            }
        ];

        // MOSTRAR VERSÍCULOS CON ANIMACIÓN ROMÁNTICA
        const contenedorVersiculos = document.getElementById("versiculos");
        versiculos.forEach((verso, index) => {
            const versoDiv = document.createElement('div');
            versoDiv.className = 'verse animated-element';
            versoDiv.style.animationDelay = `${0.3 * index}s`;
            versoDiv.innerHTML = `
                <h3>${verso.libro}</h3>
                <p>${verso.texto}</p>
            `;
            contenedorVersiculos.appendChild(versoDiv);
        });

        // FUNCIÓN PARA CREAR ELEMENTOS FLOTANTES ROMÁNTICOS
        function crearElementosFlotantes(elements, count, delayMultiplier, className) {
            const container = document.querySelector('.container');
            for (let i = 0; i < count; i++) {
                const el = document.createElement("div");
                el.innerHTML = elements[Math.floor(Math.random() * elements.length)];
                el.className = className || "floating-hearts";
                el.style.left = Math.random() * 100 + "%";
                el.style.animationDelay = Math.random() * delayMultiplier + "s";
                container.appendChild(el);
            }
        }

        // MOSTRAR SORPRESA ROMÁNTICA COMPLETA
        function mostrarSorpresa() {
            const surpriseDiv = document.getElementById("surprise");
            surpriseDiv.style.display = "block";
            document.querySelector("button").style.display = "none";
            
            // Crear lluvia romántica de elementos
            setTimeout(() => {
                crearElementosFlotantes(["💖", "❤️", "💕", "💘"], 20, 4, "floating-hearts");
                crearElementosFlotantes(["🌹", "✨", "💎", "🦋"], 15, 3, "falling-element");
                crearElementosFlotantes(["💋", "💍", "🌟", "💐"], 12, 5, "falling-element");
            }, 800);

            // Crear corazones adicionales cada 3 segundos
            setInterval(() => {
                crearElementosFlotantes(["💓", "💗", "💞"], 5, 2, "floating-hearts");
            }, 3000);
        }

        // EFECTOS ADICIONALES AL CARGAR LA PÁGINA
        window.addEventListener('load', () => {
            // Crear algunos elementos flotantes iniciales
            setTimeout(() => {
                crearElementosFlotantes(["✨", "💫"], 8, 6, "floating-hearts");
            }, 2000);
        });
    </script>
</body>
</html>