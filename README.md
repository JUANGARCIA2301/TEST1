<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Encuesta de Coordinación</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        form {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            width: 300px;
        }
        h2 {
            text-align: center;
            color: #333;
            margin-bottom: 20px;
        }
        label {
            font-weight: bold;
            display: block;
            margin-bottom: 8px;
        }
        .radio-group {
            margin-bottom: 15px;
        }
        .radio-group label {
            display: block;
            margin-bottom: 5px;
        }
        input[type="radio"] {
            margin-right: 10px;
        }
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            border: none;
            background-color: #007BFF;
            color: white;
            cursor: pointer;
            font-weight: bold;
            font-size: 16px;
            border-radius: 5px;
        }
        input[type="submit"]:hover {
            background-color: #0056b3;
        }
        .message {
            text-align: center;
            padding: 20px;
            border-radius: 8px;
            background-color: #ffffff;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <form id="myForm" action="https://script.google.com/macros/s/AKfycbxMcmQhiKAcyFIeztfND_uMZ2qyGw1VoO_c3I1omn62a-6dux0nwiF7ZjDi4Z62iOqR/exec" method="post">
        <h2>Encuesta de Coordinación</h2>
        
        <label>¿Cómo calificas a la coordinación?</label>
        <div class="radio-group">
            <label><input type="radio" name="rating" value="bueno" required> Bueno</label>
            <label><input type="radio" name="rating" value="regular" required> Regular</label>
            <label><input type="radio" name="rating" value="malo" required> Malo</label>
            <label><input type="radio" name="rating" value="sorpresa" required> Sorpresa</label>
        </div>

        <input type="submit" value="Enviar">
    </form>
    <div id="confirmation" class="message" style="display:none;">
        <h2>Gracias por tu respuesta</h2>
    </div>
</body>
</html>
