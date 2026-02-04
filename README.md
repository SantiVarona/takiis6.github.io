<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Para alguien especial ✨</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Poppins:wght@300;400;500;600&display=swap');

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      min-height: 100vh;
      background: radial-gradient(circle at top, #1b1a3a, #2b1d4d, #0f1025);
      color: #e6e6ff;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
      overflow-x: hidden;
      font-family: 'Poppins', sans-serif;
      letter-spacing: 0.2px;
    }

    .audio-hint {
      position: fixed;
      top: 15px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 0.85rem;
      opacity: 0.85;
      background: rgba(0,0,0,0.35);
      padding: 8px 14px;
      border-radius: 20px;
      z-index: 10;
      backdrop-filter: blur(6px);
      font-family: 'Poppins', sans-serif;
    }

    .stars {
      position: fixed;
      inset: 0;
      background:
        radial-gradient(2px 2px at 20% 30%, rgba(180,160,255,0.9), transparent),
        radial-gradient(2px 2px at 80% 40%, rgba(160,130,255,0.8), transparent),
        radial-gradient(1.5px 1.5px at 50% 70%, rgba(210,200,255,0.9), transparent),
        radial-gradient(2px 2px at 30% 80%, rgba(140,110,255,0.8), transparent),
        radial-gradient(1.5px 1.5px at 70% 20%, rgba(200,180,255,0.9), transparent);
      background-size: 400px 400px;
      opacity: 0.5;
      pointer-events: none;
      animation: starsMove 60s linear infinite;
    }

    .card {
      background: rgba(20, 18, 45, 0.92);
      max-width: 720px;
      width: 100%;
      border-radius: 30px;
      padding: 45px 35px;
      box-shadow: 0 30px 70px rgba(0, 0, 0, 0.6);
      animation: fadeIn 1.5s ease;
      position: relative;
    }

    .card::before {
      content: "";
      position: absolute;
      inset: -2px;
      border-radius: 32px;
      background: linear-gradient(120deg, #7f5cff, #3f8cff, #ff6fae);
      z-index: -1;
      opacity: 0.8;
    }

    h1 {
      text-align: center;
      font-size: 2.7rem;
      margin-bottom: 10px;
      color: #ff8fd6;
      text-shadow: 0 0 14px rgba(255,143,214,0.6);
      font-family: 'Playfair Display', serif;
      letter-spacing: 1px;
    }

    h2 {
      text-align: center;
      font-weight: 300;
      margin-bottom: 32px;
      font-family: 'Playfair Display', serif;
      opacity: 0.9;
    }

    p {
      font-size: 1.05rem;
      line-height: 1.9;
      margin-bottom: 22px;
      text-align: justify;
      font-weight: 300;
    }

    .highlight {
      color: #9d8cff;
      font-weight: 500;
    }

    .quote {
      margin: 38px 0;
      padding: 26px;
      background: linear-gradient(135deg, rgba(40,30,80,0.8), rgba(20,15,50,0.9));
      border-left: 6px solid #9d8cff;
      border-radius: 18px;
      font-style: italic;
      box-shadow: inset 0 0 22px rgba(157,140,255,0.35);
      font-family: 'Playfair Display', serif;
    }

    .audio-player {
      margin: 30px 0 15px;
      text-align: center;
    }

    audio {
      width: 100%;
      max-width: 400px;
      outline: none;
      border-radius: 20px;
    }

    .cta { text-align: center; margin-top: 24px; }

    button {
      background: linear-gradient(135deg, #7f5cff, #ff6fae);
      color: #ffffff;
      border: none;
      padding: 14px 28px;
      border-radius: 30px;
      font-size: 0.95rem;
      cursor: pointer;
      font-weight: 500;
      letter-spacing: 0.5px;
      transition: transform 0.2s, box-shadow 0.2s;
      box-shadow: 0 12px 30px rgba(127,92,255,0.6);
      font-family: 'Poppins', sans-serif;
    }

    button:hover {
      transform: scale(1.08);
      box-shadow: 0 18px 40px rgba(127,92,255,0.8);
    }

    .heart {
      text-align: center;
      font-size: 3rem;
      margin-top: 10px;
      animation: beat 1.2s infinite;
    }

    footer {
      text-align: center;
      margin-top: 32px;
      font-size: 0.85rem;
      color: #bfaaff;
      font-weight: 300;
      letter-spacing: 0.6px;
    }

    @keyframes starsMove {
      from { transform: translateY(0); }
      to { transform: translateY(-400px); }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes beat {
      0%, 100% { transform: scale(1) rotate(0deg); }
      50% { transform: scale(1.25) rotate(-5deg); }
    }
  </style>
</head>
<body>
  <div class="audio-hint">🔊 Toca la pantalla si no escuchas la música</div>
  <div class="stars"></div>
  <div class="card">
    <h1>Para ti 💖</h1>
    <h2>Alguien que llegó sin aviso… y se quedó</h2>

    <p>
      Tal vez no somos nada todavía, o tal vez somos <span class="highlight">más de lo que creemos</span>.
      Lo único seguro es que desde que apareciste, hay días que se sienten distintos,
      más ligeros, más bonitos.
    </p>

    <p>
      Esta página no es una promesa ni una presión. Es solo un detalle.
      Una forma sincera de decir que me importas, que me gusta escucharte,
      que pienso en ti más veces de las que admitiría en voz alta.
    </p>

    <div class="quote">
      “No sé qué seamos, pero sé que cuando sonríes,
      algo en mí también lo hace.”
    </div>

    <p>
      Si algún día decides quedarte, aquí estaré.
      Y si no, gracias igual por existir y por inspirar algo tan bonito
      como este pequeño rincón en internet.
    </p>

    <div class="audio-player">
      
      <audio id="bgMusic" autoplay loop muted>
        <source src="Escapism.mp3" type="audio/mpeg">
        Tu navegador no soporta audio HTML5.
      </audio>
      
    </div>

    <div class="heart">❤️</div>

    <div class="cta">
      <button onclick="mostrarMensaje()">¿Seguimos escribiendo esta historia?</button>
      <p id="mensaje" style="display:none; margin-top:15px; font-style:italic;">Sin prisas, sin etiquetas… solo siendo nosotros.</p>
    </div>

    <footer>
      Hecho con cariño por <strong>El posible amor de tu vida <3</strong>
    </footer>
  </div>
<script>
    function mostrarMensaje() {
      document.getElementById('mensaje').style.display = 'block';
    }

    const music = document.getElementById('bgMusic');

    document.addEventListener('click', () => {
      if (music.muted) {
        music.muted = false;
        music.volume = 0.6;
      }
    }, { once: true });
  </script>
</body>
</html>
