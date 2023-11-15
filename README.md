<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dispositivos de E/S - Cámara</title>
    <link rel="icon" href="data:;base64,iVBORw0KGgo=" />
    <link rel="stylesheet" href="camara.css">
    <script defer src="camara.js"></script>
</head>

<body>
    <button id="iniciar-camara">Iniciar la cámara</button>
    <video id="video" width="320" height="240" autoplay></video>
    <button id="clic-foto">Tomar foto</button>
    <div id="dataurl-container">
        <canvas id="canvas" width="320" height="240"></canvas>
        <div id="dataurl-header">Data URL de la imagen</div>
        <textarea id="dataurl" readonly></textarea>
    </div>
</body>

</html>
