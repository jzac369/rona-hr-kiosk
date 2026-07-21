# RONA HR Kiosk

Informačný systém pre HR oddelenie spoločnosti RONA — jednosúborová HTML aplikácia určená pre Android tablet v landscape orientácii, umiestnený v čakárni HR oddelenia.

## Obsah
- Prehľad voľných pozícií (sklár, zoraďovač, odnášač, strojník, upratovačka, skladník, údržbár, administratíva)
- Formulár "Mám záujem" so zberom kontaktných údajov a GDPR súhlasom
- Priebeh náborového procesu (5 krokov)
- Benefity zamestnancov
- O spoločnosti
- Časté otázky (FAQ)
- Kontakt na HR tím
- Idle/screensaver režim, prístupnostné ovládanie veľkosti textu

## Použitie
Súbor `index.html` je plne samostatný (logo je vložené ako base64), stačí ho otvoriť v prehliadači alebo nasadiť cez kiosk prehliadač (napr. Fully Kiosk Browser) na tablete.

⚠️ Formulár momentálne ukladá dáta len lokálne (localStorage) v prehliadači. Pre reálne odosielanie záujemcov do HR systému je potrebné napojiť backend (napr. Firebase/Firestore alebo API).
