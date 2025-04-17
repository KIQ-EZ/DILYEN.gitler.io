<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Dilyen gitler</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        .title {
            font-size: 60px;
            font-weight: bold;
            color: #00e0ff;
            text-shadow: 0 0 20px #00e0ff, 0 0 40px #00e0ff;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
                text-shadow: 0 0 20px #00e0ff, 0 0 40px #00e0ff;
            }
            50% {
                transform: scale(1.05);
                text-shadow: 0 0 30px #00ffff, 0 0 60px #00ffff;
            }
        }
    </style>
</head>
<body>
    <div class="title">Dilyen gitler</div>
</body>
</html>