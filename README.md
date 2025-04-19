<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slik_TZ README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        h1 {
            animation: fadeIn 2s;
        }
        p {
            animation: slideIn 2s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        .tech-problems {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .problem {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            margin: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            width: 200px;
            transition: transform 0.3s;
        }
        .problem:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <h1>Welcome to Slik_TZ</h1>
    <p>Your solution to various tech problems!</p>
    <div class="tech-problems">
        <div class="problem">🔧 Problem 1: Bug Fixing</div>
        <div class="problem">💻 Problem 2: Software Development</div>
        <div class="problem">🔒 Problem 3: Security Solutions</div>
        <div class="problem">📊 Problem 4: Data Analysis</div>
        <div class="problem">🌐 Problem 5: Web Development</div>
    </div>
</body>
</html>
