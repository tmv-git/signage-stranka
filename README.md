# Uvítacia obrazovka

Otvorte `index.html` v prehliadači na kioskovej obrazovke. Všetky súbory ponechajte v rovnakom priečinku.

## Wi-Fi pre hostí

V súbore `wifi-config.js` doplňte heslo do položky `password` a obnovte stránku. Úvodzovky a spätné lomky v hesle musia byť v JavaScripte zapísané ako `\"` a `\\`. QR kód sa bez hesla nezobrazí. Nastavenie je určené pre zabezpečenie WPA/WPA2/WPA3.

Heslo je uložené v súbore ako čitateľný text a obsahuje ho aj QR kód, preto používajte iba sieť určenú pre hostí a súbory nezverejňujte.

## Počasie

Počasie pre Trenčín, Bratislavu, Žilinu, Nitru, Košice a Banskú Bystricu poskytuje [Open-Meteo](https://open-meteo.com/). Na načítanie je potrebné internetové pripojenie; údaje sa obnovujú každých 15 minút. Pri výpadku sa pri príslušnom meste zobrazí upozornenie a stránka to skúsi znova pri ďalšom obnovení.

Ikony vyjadrujú stav počasia a pri jasnej oblohe rozlišujú deň a noc. Ich vzhľad závisí od podpory emoji v zariadení.

QR kód sa vytvára lokálne pomocou knižnice qrcode-generator; jej licencia je v súbore `qrcode-LICENSE.txt`.

## Meniny

Meniny sa zobrazujú podľa miestneho dátumu zariadenia a aktualizujú sa po polnoci. Údaje sú uložené v `meniny.js`, preto fungujú aj bez internetu. Dni bez mena v použitom kalendári sa zobrazia s upozornením.

Údaje pochádzajú z projektu [SKCalendar](https://github.com/ezekiell/SKCalendar) (stav z roku 2016); licencia je v súbore `meniny-LICENSE.txt`. Zoznam možno upraviť v `meniny.js`.

## Fotografie

Fotografie v uvítacej časti sa striedajú každých 15 sekúnd. Ich zoznam a poradie možno upraviť v poli `photos` v súbore `index.html`. Prvá fotografia je nastavená aj priamo v HTML, aby sa zobrazila ihneď po načítaní stránky.

OK
