<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Messaggistica</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div id="app">
        <div id="setup">
            <h2>Configura il tuo numero</h2>
            <input type="text" id="yourName" placeholder="Il tuo nome">
            <input type="tel" id="yourNumber" placeholder="Il tuo numero di telefono">
            <button id="saveNumberBtn">Salva</button>
        </div>
        <div id="mainApp" class="hidden">
            <div id="sidebar">
                <button id="addContactBtn">Aggiungi Contatto</button>
                <div id="addContactForm" class="hidden">
                    <input type="text" id="contactName" placeholder="Nome contatto">
                    <input type="tel" id="contactNumber" placeholder="Numero contatto">
                    <button id="saveContactBtn">Salva Contatto</button>
                </div>
                <div id="contacts">
                    <h3>Contatti</h3>
                    <ul id="contactList"></ul>
                </div>
            </div>
            <div id="chatWindow">
                <div id="chatHeader">
                    <h3 id="chatWith"></h3>
                </div>
                <div id="messages"></div>
                <div id="messageInput">
                    <textarea id="messageBox" placeholder="Scrivi un messaggio..." disabled></textarea>
                    <input type="file" id="imageInput" accept="image/*" disabled>
                    <button id="sendBtn" disabled>Invia</button>
                </div>
            </div>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
