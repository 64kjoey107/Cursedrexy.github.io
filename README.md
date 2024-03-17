<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #006699, #000000);
            color: #fff;
        }
        header {
            background-color: rgba(0, 0, 0, 0.5);
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 10px;
            text-align: center;
        }
        nav span {
            color: #fff;
            margin: 0 10px;
            cursor: pointer;
        }
        .section-wrapper {
            margin: 20px;
            border-radius: 10px;
            background-color: rgba(255, 255, 255, 0.1);
            padding: 20px;
        }
        .section-wrapper:hover {
            background-color: rgba(255, 255, 255, 0.3);
        }
        section h2 {
            font-size: 24px;
            text-align: center;
            margin-bottom: 20px;
            text-transform: uppercase;
        }
        section p {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 10px;
        }
        section button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin-right: 10px;
            margin-bottom: 10px;
            transition: background-color 0.3s ease;
            display: block;
            width: 100%;
        }
        section button:hover {
            background-color: #555;
        }
        footer {
            background-color: rgba(0, 0, 0, 0.5);
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cursedrexy hub</h1>
    </header>
    <nav>
        <span onclick="location.href='https://example.com';">Home</span>
        <span onclick="location.href='https://example.com';">Certificate</span>
        <span onclick="location.href='https://example.com';">Direct Install</span>
        <span onclick="location.href='https://example.com';">DNS Method</span>
    </nav>
    <div class="section-wrapper">
        <section id="home">
            <h2>Home</h2>
            <button onclick="window.location.href = 'https://discord.gg/asH3SMNvX4';">Discord</button>
        </section>
    </div>
    <div class="section-wrapper">
        <section id="certificate">
            <h2>Certificate</h2>
            <button onclick="window.location.href = 'https://example.com/certificate1';">Button 1</button>
            <button onclick="window.location.href = 'https://example.com/certificate2';">Button 2</button>
            <button onclick="window.location.href = 'https://example.com/certificate3';">Button 3</button>
            <button onclick="window.location.href = 'https://example.com/certificate4';">Button 4</button>
        </section>
    </div>
    <div class="section-wrapper">
        <section id="directInstall">
            <h2>Direct Install</h2>
            <button onclick="window.location.href = 'https://example.com/directInstall1';">ArceusX Direct Install</button>
            <button onclick="window.location.href = 'https://example.com/directInstall2';">Codex Direct Install</button>
            <button onclick="window.location.href = 'https://example.com/directInstall3';">Button 3</button>
            <button onclick="window.location.href = 'https://example.com/directInstall4';">Button 4</button>
        </section>
    </div>
    <div class="section-wrapper">
        <section id="dnsMethod">
            <h2>DNS Method</h2>
            <button onclick="window.location.href = 'https://example.com/dnsMethod1';">Button 1</button>
            <button onclick="window.location.href = 'https://example.com/dnsMethod2';">Button 2</button>
            <button onclick="window.location.href = 'https://example.com/dnsMethod3';">Button 3</button>
            <button onclick="window.location.href = 'https://example.com/dnsMethod4';">Button 4</button>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
