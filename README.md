# Boekenkast

Leesdagboek voor op de telefoon. Boeken toevoegen via de streepjescode, zoeken op titel of zelf invullen.

## Online zetten met GitHub Pages
1. Maak op GitHub een nieuwe repository, bijvoorbeeld `boekenkast` (mag openbaar zijn; de boeken zelf staan niet in de repo, alleen op de telefoon).
2. Upload alle bestanden uit deze map via *Add file > Upload files*.
3. Ga naar *Settings > Pages*, kies bij *Source* "Deploy from a branch", branch `main`, map `/ (root)`, en sla op.
4. Na een minuut staat de app op `https://<jouw-gebruikersnaam>.github.io/boekenkast/`.

## Op de telefoon
- iPhone: open de link in Safari, tik op Delen > Zet op beginscherm.
- Android: open de link in Chrome, menu (drie puntjes) > Toevoegen aan startscherm.

Open de app daarna altijd via het icoon op het beginscherm.

## Waar staan de gegevens?
Alleen op de telefoon zelf (in de browseropslag). Via Instellingen > Back-up maken download je een bestand met alle boeken; met Back-up terugzetten zet je het terug, ook op een andere telefoon.

## Gebruikte bronnen
- Boekgegevens: Google Books API en Open Library API (gratis, geen sleutel nodig).
- Barcodescanner: html5-qrcode 2.3.8 (Apache 2.0, meegeleverd).
