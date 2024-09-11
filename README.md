<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Geschichtspräsentation - Grenzen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://example.com/hintergrundbild.jpg'); /* Füge hier dein Hintergrundbild ein */
            background-size: cover;
            background-attachment: fixed;
        }

        .header {
            text-align: center;
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 20px;
            font-size: 2.5em;
            letter-spacing: 2px;
        }

        .container {
            display: flex;
            justify-content: space-between;
            margin: 20px;
        }

        .side {
            width: 20%;
            display: flex;
            flex-direction: column;
            justify-content: space-around; /* Verteilt die Buttons */
            padding: 20px;
        }

        .button {
            background-color: #333;
            color: white;
            border: none;
            padding: 15px 30px;
            text-align: center;
            font-size: 16px;
            margin: 20px 0; /* Mehr Abstand zwischen den Buttons */
            cursor: pointer;
            width: 100%;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #555;
        }

        .content {
            width: 60%;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .image-frame {
            width: 80%;
            height: 400px;
            border: 2px solid #333;
            margin: 40px 0; /* Mehr Abstand zwischen den Bildern */
            background-color: white;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        img {
            max-width: 100%;
            max-height: 100%;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <!-- Überschrift -->
    <div class="header">
        <h1>Geschichtspräsentation: Grenzen in der Geschichte</h1>
    </div>

    <!-- Hauptcontainer -->
    <div class="container">
        <!-- Linke Seite mit Links -->
        <div class="side">
            <button class="button" onclick="window.location.href='https://dein-link1.com'">Link 1</button>
            <button class="button" onclick="window.location.href='https://dein-link2.com'">Link 2</button>
            <button class="button" onclick="window.location.href='https://dein-link3.com'">Link 3</button>
        </div>

        <!-- Mittlerer Bereich mit Bilderrahmen -->
        <div class="content">
            <div class="image-frame">
                <!-- Hier kannst du ein Bild einfügen -->
                <img src="https://example.com/bild1.jpg" alt="Beispiel 1">
            </div>
            <div class="image-frame">
                <!-- Hier kannst du ein Bild einfügen -->
                <img src="https://example.com/bild2.jpg" alt="Beispiel 2">
            </div>
            <div class="image-frame">
                <!-- Hier kannst du ein Bild einfügen -->
                <img src="https://example.com/bild3.jpg" alt="Beispiel 3">
            </div>
        </div>

        <!-- Rechte Seite mit Links -->
        <div class="side">
            <button class="button" onclick="window.location.href='https://dein-link4.com'">Link 4</button>
            <button class="button" onclick="window.location.href='https://dein-link5.com'">Link 5</button>
            <button class="button" onclick="window.location.href='https://dein-link6.com'">Link 6</button>
        </div>
    </div>

    <!-- Fußzeile -->
    <footer>
        © 2024 Geschichtspräsentation: Grenzen in der Geschichte
    </footer>

</body>
</html>
