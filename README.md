# Smartshop-
Einfacher einkaufen 
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>SmartShop</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>SmartShop – Smarter Einkaufen</h1>

    <section id="coupons">
        <h2>Wöchentliche Coupons</h2>
        <ul id="coupon-list">
            <li>REWE – 10% auf Obst</li>
            <li>Lidl – 1+1 gratis auf Pasta</li>
            <li>Edeka – 20% auf vegane Produkte</li>
        </ul>
    </section>

    <section id="einkaufsliste">
        <h2>Deine Einkaufsliste</h2>
        <input type="text" id="item-input" placeholder="z. B. Milch hinzufügen">
        <button onclick="addItem()">Hinzufügen</button>
        <ul id="item-list"></ul>
    </section>

    <section id="rezepte">
        <h2>Rezept-Idee der Woche</h2>
        <p><strong>Nudeln mit Tomatensoße</strong></p>
        <ul>
            <li>Nudeln – 0,79€ (Lidl)</li>
            <li>Tomatensoße – 1,29€ (REWE)</li>
            <li>Basilikum – 0,99€ (Edeka)</li>
        </ul>
    </section>

    <script src="script.js"></script>
</body>
</html>
