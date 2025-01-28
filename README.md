<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lista de Canais</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
            text-align: center;
        }

        h1 {
            color: #333;
            margin-bottom: 20px;
        }

        .channel-list {
            max-width: 600px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .channel {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 15px;
            border-bottom: 1px solid #ddd;
        }

        .channel:last-child {
            border-bottom: none;
        }

        .channel img {
            width: 50px;
            height: 50px;
            border-radius: 10px;
            margin-right: 15px;
        }

        .channel-info {
            text-align: left;
            flex-grow: 1;
        }

        .channel-info h3 {
            margin: 0;
            font-size: 18px;
            color: #333;
        }

        .channel-info p {
            margin: 5px 0 0;
            color: #777;
            font-size: 14px;
        }

        .channel a {
            text-decoration: none;
            background-color: #007BFF;
            color: #fff;
            padding: 8px 12px;
            border-radius: 5px;
            font-size: 14px;
        }

        .channel a:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Lista de Canais</h1>
    <div class="channel-list">
        <!-- Canal 1 -->
        <div class="channel">
            <img src="https://via.placeholder.com/50" alt="Logo Canal 1">
            <div class="channel-info">
                <h3>Canal 1</h3>
                <p>Descrição do canal 1</p>
            </div>
            <a href="https://example.com/canal1" target="_blank">Assistir</a>
        </div>

        <!-- Canal 2 -->
        <div class="channel">
            <img src="https://via.placeholder.com/50" alt="Logo Canal 2">
            <div class="channel-info">
                <h3>Canal 2</h3>
                <p>Descrição do canal 2</p>
            </div>
            <a href="https://example.com/canal2" target="_blank">Assistir</a>
        </div>

        <!-- Canal 3 -->
        <div class="channel">
            <img src="https://via.placeholder.com/50" alt="Logo Canal 3">
            <div class="channel-info">
                <h3>Canal 3</h3>
                <p>Descrição do canal 3</p>
            </div>
            <a href="https://example.com/canal3" target="_blank">Assistir</a>
        </div>
    </div>
</body>
</html>
