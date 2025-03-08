<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FAQ - Dein Name</title>
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
            <strong>Wer bist du?</strong>
            <div class="faq-answer">Ich bin Efehan Berkay Karaogullari, ein Gaming- und Technikinteressierter!</div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(1)">
            <strong>Welches Mikrofon benutzt du?</strong>
            <div class="faq-answer">Ich benutze das Shure MV7 zusammen mit einem GoXLR Mini.</div>
        </div>
        <div class="faq-item" onclick="toggleAnswer(2)">
            <strong>Welche Grafikkarte hast du?</strong>
            <div class="faq-answer">Ich verwende die ASRock RX 7600 XT.</div>
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
