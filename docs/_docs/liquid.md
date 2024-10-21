<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sito con Sfondo Scuro</title>
    <style>
        body {
            background-color: #ffffff; /* Sfondo scuro neutro */
            color: #2c2c2c; /* Colore del testo chiaro */
            font-family: 'Helvetica', 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .header {
            background-color: #1f1e1b; /* Sfondo uguale al pie' di pagina */
            color: #ffffff; /* Testo bianco */
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: relative;
        }

        /* Stile per il logo rotondo */
        .header .logo {
            height: 50px; /* Altezza del logo */
            width: 50px;  /* Larghezza del logo */
            border-radius: 50%; /* Logo rotondo */
            margin-right: 20px;
        }

        /* Stile per il titolo al centro */
        .header .title {
            text-align: center;
            font-size: 28px;
            font-weight: bold;
            letter-spacing: 1px;
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
        }
        
        .header .spacer {
            flex: 1;
        }
        /* Stile per la selezione delle lingue */
        .header .language-select {
            font-size: 14px;
            color: #ffffff;
        }

        .header .language-select select {
            background-color: #1f1e1b;
            color: #ffffff;
            border: 1px solid #ffffff;
            padding: 5px;
            font-size: 14px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .video-section {
            text-align: center;
            margin-bottom: 50px;
        }

        .video-section video {
            border-radius: 15px; /* Bordi curvi per il video */
            width: 100%; /* Adatta il video alla larghezza del contenitore */
        }

        .row {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            margin-bottom: 50px;
        }

        .row .image-left, .row .image-right {
            flex: 1;
            max-width: 50%;
        }

        .row .text {
            flex: 1;
            max-width: 50%;
            padding: 20px;
        }

        .row .image-left img, .row .image-right img {
            width: 100%;
            height: auto;
            border-radius: 15px;
        }

        .footer {
            background-color: #1f1e1b; /* Sfondo grigio scuro simile a ChatGPT */
            color: #ffffff; /* Testo bianco */
            padding: 20px;
            text-align: left;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .footer .footer-content {
            display: flex;
            align-items: center;
        }

        .footer img {
            height: 40px; /* Altezza del logo */
            margin-right: 10px; /* Spazio tra il logo e la scritta */
            border-radius: 50%;
        }

        .footer p {
            margin: 5px 0;
        }

        /* Media query per dispositivi mobili */
        @media (max-width: 768px) {
            .row {
                flex-direction: column;
                text-align: center;
            }

            .row .image-left, .row .image-right, .row .text {
                max-width: 100%;
                padding: 10px;
            }
        }
        .header .language-select {
            display: flex;
            align-items: center;
            font-size: 14px;
        }

        /* Stile per le bandiere */
        .header .language-select img {
            width: 25px;
            height: 25px;
            margin-right: 8px;
            border-radius: 3px; /* Bordi leggermente arrotondati per le bandiere */
        }

        /* Stile per l'opzione della lingua */
        .header .language-option {
            display: flex;
            align-items: center;
            padding: 5px;
        }

        /* Stile per l'opzione della lingua (link) */
        .header .language-option a {
            color: #ffffff; /* Testo bianco */
            text-decoration: none; /* Rimuove la sottolineatura */
        }
    </style>
</head>
<body>
    <div class="header">
        <!-- Logo rotondo a sinistra -->
        <div class="logo-container">
            <img src="c:\Users\Emanuele\Desktop\Emanuele\Scuola\INFORMATICA\Html,Css,JS\prova\LOGO B5E.png" alt="Logo" class="logo">
        </div>
        
        <!-- Titolo al centro -->
        <div class="title">
            The Big Five Experience
        </div>

        <!-- Selezione della lingua a destra -->
        <div class="language-select">
            <div class="language-option">
                <a href="prova 1.html">
                <img src="https://flagcdn.com/it.svg" alt="Italiano">
                
            </a>
            </div>
            <div class="language-option">
                <a href="try 1.html">
                <img src="https://flagcdn.com/gb.svg" alt="English">
                
            </a>
            </div>
            <div class="language-option">
                <a href="link_a_tua_pagina.html">
                <img src="https://flagcdn.com/fr.svg" alt="Français">
                
            </a>
            </div>
            <div class="language-option">
                <a href="link_a_tua_pagina.html">
                <img src="https://flagcdn.com/de.svg" alt="Deutsch">
                
            </a>
            </div>
        </div>
    </div>
    <div class="container">
        <!-- Sezione video -->
        <div class="video-section">
            <!-- Qui puoi aggiungere il tuo video in un secondo momento -->
            
            <p><div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/1021856968?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="VIDEO AI NOLI voce"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script></p>
        </div>

        <!-- Prima sezione: immagine a sinistra e testo a destra -->
        <div class="row">
            <div class="image-left">
                <!-- Qui aggiungerai l'immagine -->
                <a href="https://ibb.co/3T5j6LB"><img src="https://i.ibb.co/51XSpfB/marco-btw-32798-a-cinematic-images-of-crusader-warriors-that-0ce38a6b-3b99-46d9-9ffe-3ff16c8432b5-2.png" alt="marco-btw-32798-a-cinematic-images-of-crusader-warriors-that-0ce38a6b-3b99-46d9-9ffe-3ff16c8432b5-2" border="0"></a>
            </div>
            <div class="text">
                <h2>Capitolo I: Noli e il periodo delle Crociate</h2>
                <p>Nel pieno del Medioevo, il Mediterraneo era un mare in tumulto: Crociati, Saraceni e mercanti attraversavano le sue acque, portando con sé conflitti, idee e scambi commerciali. Noli, grazie alla sua flotta e alla sua posizione strategica, giocò un ruolo chiave durante il periodo delle Crociate.
                    La sua vicinanza al porto di Genova e la sua capacità di offrire riparo ai naviganti la resero una città importante per i Crociati in viaggio verso la Terra Santa. Non solo forniva navi, ma spesso i suoi abitanti partecipavano direttamente alle spedizioni. Si narra che i cavalieri di Noli abbiano combattuto coraggiosamente durante la terza crociata, al fianco di famosi condottieri come Riccardo Cuor di Leone. Una piccola città che seppe dare grandi contributi a un’impresa tanto lontana, alimentando leggende su audaci marinai e guerrieri.</p>
            </div>
        </div>

        <!-- Seconda sezione: immagine a destra e testo a sinistra -->
        <div class="row">
            <div class="text">
                <h2>Capitolo IV: Il castello di Monte Ursino – Il monumento difensivo di Noli</h2>
                <p>Imponente e maestoso, il Castello di Monte Ursino domina il panorama di Noli. Costruito probabilmente nel X secolo, il castello divenne il baluardo difensivo della città contro le incursioni nemiche. Situato sulla collina che sovrasta il borgo, la fortezza era parte di un sistema difensivo che comprendeva anche mura e torri. Da qui, i soldati nolani potevano avvistare in anticipo le navi pirata o gli eserciti in avvicinamento.
                    Nel corso dei secoli, il castello vide numerose battaglie e assedi, ma rimase sempre simbolo di forza e indipendenza. Una leggenda narra che, durante un attacco saraceno, una giovane donna del paese avesse scalato le mura del castello e lanciato pietre contro gli invasori, salvando così la città. Questo evento sarebbe stato all'origine della tradizione locale che vuole le donne nolane coraggiose e indomabili.</p>
            </div>
            <div class="image-right">
                <!-- Qui aggiungerai l'immagine -->
                <a href="https://ibb.co/y4JsKbT"><img src="https://i.ibb.co/41xNC5y/marco-btw-32798-httpss-mj-runp-LMob-SEQw-Uw-turn-this-photo-into-698f00d2-9fc3-428c-a3eb-863564ea492.png" alt="marco-btw-32798-httpss-mj-runp-LMob-SEQw-Uw-turn-this-photo-into-698f00d2-9fc3-428c-a3eb-863564ea492" border="0"></a>
            </div>
        </div>
    </div>
    <div class="footer">
        <div class="footer-content">
            <!-- Logo sulla sinistra -->
            <img src="c:\Users\Emanuele\Desktop\Emanuele\Scuola\INFORMATICA\Html,Css,JS\prova\LOGO B5E.png" alt="Logo">
            <!-- Prima scritta con il logo accanto -->
            <p><h4>The Big Five Experience</h4></p>
        </div>
        <!-- Altre due scritte sotto -->
         <p><h2>Contattaci</h2></p>
        <p>Email: studiofotograficolinomarino@gmail.com</p>
        <p>Recapito telefonico: +39 347 226 1208</p>
    </div>
</body>
</html>
