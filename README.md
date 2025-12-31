<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Para Ti 💖</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      color: #333;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }.card {
  background: white;
  width: 90%;
  max-width: 500px;
  border-radius: 20px;
  padding: 25px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
  text-align: center;
  animation: fadeIn 1.5s ease;
}

h1 {
  color: #e75480;
}

p {
  font-size: 1.1em;
  line-height: 1.6;
}

button {
  margin-top: 15px;
  padding: 12px 20px;
  border: none;
  border-radius: 30px;
  background: #e75480;
  color: white;
  font-size: 1em;
  cursor: pointer;
  transition: transform 0.2s, background 0.2s;
}

button:hover {
  background: #d6456d;
  transform: scale(1.05);
}

.hidden {
  display: none;
  margin-top: 15px;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

.heart {
  font-size: 2em;
  animation: beat 1s infinite;
}

@keyframes beat {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.2); }
}

  </style>
</head>
<body>
  <div class="card">
    <h1>Hola, mi amor 💕</h1>
    <p>
      Hice esta pequeña página solo para ti.
      No es perfecta, pero está hecha con cariño,
      pensando en tu sonrisa.
    </p><div class="heart">❤️</div>

<button onclick="mostrarMensaje()">Toca aquí</button>

<div id="mensaje" class="hidden">
  <p>
    Gracias por existir, por hablar conmigo,
    por hacer mis días más bonitos.
    Me importas más de lo que imaginas.
  </p>
</div>

  </div>  <script>
    function mostrarMensaje() {
      const msg = document.getElementById('mensaje');
      msg.classList.toggle('hidden');
    }
  </script></body>
</html>
