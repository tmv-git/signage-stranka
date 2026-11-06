# Uvítacia obrazovka

Otvorte `index.html` v prehliadači na kioskovej obrazovke. Všetky súbory ponechajte v rovnakom priečinku.

## Wi-Fi pre hostí

V súbore `wifi-config.js` doplňte heslo do položky `password` a obnovte stránku. Úvodzovky a spätné lomky v hesle musia byť v JavaScripte zapísané ako `\"` a `\\`. QR kód sa bez hesla nezobrazí. Nastavenie je určené pre zabezpečenie WPA/WPA2/WPA3.

Heslo je uložené v súbore ako čitateľný text a obsahuje ho aj QR kód, preto používajte iba sieť určenú pre hostí a súbory nezverejňujte.

## Počasie

Počasie pre Trenčín, Bratislavu, Žilinu, Nitru, Košice a Banskú Bystricu poskytuje [Open-Meteo](https://open-meteo.com/). Na načítanie je potrebné internetové pripojenie; údaje sa obnovujú každých 15 minút. Pri výpadku sa pri príslušnom meste zobrazí upozornenie a stránka to skúsi znova pri ďalšom obnovení.

QR kód sa vytvára lokálne pomocou knižnice qrcode-generator; jej licencia je v súbore `qrcode-LICENSE.txt`.

OK
