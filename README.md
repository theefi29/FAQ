<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FAQ - Efehan Berkay Karaogullari</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f8f9fa;
        }
        h1 {
            text-align: center;
        }
        .faq-container {
            margin-top: 20px;
        }
        .faq-item {
            background: white;
            padding: 15px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: 1px solid #ddd;
            cursor: pointer;
        }
        .faq-answer {
            display: none;
            margin-top: 10px;
            color: #555;
        }
    </style>
</head>
<body>
    <h1>Häufig gestellte Fragen</h1>
    <div class="faq-container">
        <div class="faq-item" onclick="toggleAnswer(0)">
            <strong>Wie heißt du?</strong>
            <div class="faq-answer">Efi.</div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(1)">
            <strong>Wie alt bist du?</strong>
            <div class="faq-answer">02.03.2009.</div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(2)">
            <strong>Wo wohnst du?</strong>
            <div class="faq-answer">Im Nirgendwo.</div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(3)">
            <strong>Wie siehst du aus?</strong>
            <div class="faq-answer">Richtig Cozy. 😎</div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(4)">
            <strong>Was für Hardware und Software benutzt du?</strong>
            <div class="faq-answer">
                <strong>PC:</strong><br>
                - Prozessor: AMD Ryzen 5 7600<br>
                - Grafikkarte: ASRock RX 7600 XT<br>
                - RAM: 32Gb <br>
                <strong>Audio:</strong><br>
                - Mikrofon: Eins von FIFINE (macht seinen Job)<br>
                - Audio-Interface: U-PHORIA UMC22<br><br>
                <strong>Software:</strong><br>
                - Aufnahme: OBS Studio<br>
                - Videoschnitt: Adobe Premiere Pro<br>
                - Bildbearbeitung: Adobe Photoshop<br>
            </div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(5)">
            <strong>Auf welchen sozialen Plattformen bist du unterwegs?</strong>
            <div class="faq-answer">
                YouTube : https://www.youtube.com/@efi_029 <br>
                Twitter: https://x.com/efi_29 <br>
                Twitch: (geplant) <br>
                Discord: (geplant) <br>
                Instagram: (geplant) <br>
                TikTok: (geplant) <br>    
            </div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(6)">
            <strong>Hast du Geschwister oder Haustiere?</strong>
            <div class="faq-answer">Nein, hab keine Geschwister will mir aber irgendwann ne Katze kaufen.</div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(7)">
            <strong>Arbeitest du oder gehst du zur Schule?</strong>
            <div class="faq-answer">Gehe noch zur Schule</div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(8)">
            <strong>Was sind deine Lieblingsspiele?</strong>
            <div class="faq-answer">
                - Elden Ring<br>
                - Subnautica<br>
                - Five Nights At Freddys<br>
                - Minecraft<br>
                - Grounded<br>
                - Satisfactory<br>
                - Rainbow Six<br>
                - Poppy Playtime<br>
                - Dead Island 2<br>
                - It Takes Two<br>
            </div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(9)">
            <strong>Was sind deine Hobbys?</strong>
            <div class="faq-answer">
                - Videospiele<br>
                - Zeichnen<br>
                - Sport<br>
                - Videoschnitt<br>
                - Motorradfahren (habe ne Yamaha YZF R125)<br>
            </div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(10)">
            <strong>Was ist deine Lieblingsfarbe?</strong>
            <div class="faq-answer">Hell Balu sowie Violett.</div>
        </div>
    </div>

    <script>
        function toggleAnswer(index) {
            var answers = document.querySelectorAll('.faq-answer');
            answers[index].style.display = answers[index].style.display === 'block' ? 'none' : 'block';
        }
    </script>
</body>
</html>
