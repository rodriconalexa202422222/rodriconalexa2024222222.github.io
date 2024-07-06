<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Prueba</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: url('https://www.transparenttextures.com/patterns/white-jeans.png') repeat;
            margin: 0;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            background-color: #ff69b4; /* Color rosa */
            color: white;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        .message {
            display: none;
            margin-top: 20px;
            font-size: 24px;
            color: #ff1493; /* Color rosa fuerte */
        }
    </style>
</head>
<body>
    <div>
        <button onclick="showMessage()">Click Aquí</button>
        <div id="message" class="message">Te quiero Alexa mua <3</div>
    </div>
    <script>
        function showMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>
</body>
</html>
