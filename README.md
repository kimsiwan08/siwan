<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .warning {
            font-size: 18px;
            color: red;
            font-weight: bold;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <h2>About This Website</h2>
        <p>This is a simple website created using HTML, CSS, and JavaScript.</p>
        <button onclick="showMessage()">Click Me</button>
        
        <!-- 여기에 문구 추가 -->
        <p class="warning">사진우 개빡치게 하지마</p>
    </main>
    <footer>
        <p>&copy; 2025 Your Name. All Rights Reserved.</p>
    </footer>
    <script>
        function showMessage() {
            alert("Thanks for visiting!");
        }
    </script>
</body>
</html>
