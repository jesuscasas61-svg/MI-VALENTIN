<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>¿Quieres ser mi Valentín?</title>

<style>
body {
    background: linear-gradient(to right, #ff9a9e, #fad0c4);
    text-align: center;
    font-family: Arial, sans-serif;
    margin-top: 100px;
    transition: background 1s ease;
}

h1 {
    font-size: 40px;
    color: white;
}

button {
    padding: 15px 30px;
    font-size: 20px;
    margin: 20px;
    border: none;
    border-radius: 10px;
    cursor: pointer;
}

#si {
    background-color: #ff4d6d;
    color: white;
}

#no {
    background-color: gray;
    color: white;
}

#mensaje {
    margin-top: 40px;
    font-size: 25px;
    color: white;
}

.grande {
    font-size: 80px;
}
</style>

</head>
<body>

<h1>💘 ¿Quieres ser mi Valentín? 💘</h1>

<button id="si" onclick="aceptar()">Sí 💖</button>
<button id="no" onclick="rechazar()">No 😢</button>

<div id="mensaje"></div>

<script>
function aceptar() {
    document.body.style.background = "#ff0000";
    document.getElementById("mensaje").innerHTML = `
        <h2>🎉 ¡Felicidades mi amor! 💘</h2>
        <div class="grande">❤️</div>
        <div class="grande">🐵🐵🐵</div>
        <p>Ahora oficialmente eres mi Valentín 💖</p>
    `;
}

function rechazar() {
    document.getElementById("mensaje").innerHTML =
    "<h3>😏 Opción incorrecta... Reintentar 💕</h3>";
}
</script>

</body>
</html>
