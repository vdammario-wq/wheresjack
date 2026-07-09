# Where's Jack?

Een kleine app om bij te houden bij wie de hond Jack is in co-ouderschap, en om het evenwicht in dagen tussen Mario en Kurt te berekenen. De app is te installeren op je telefoon en werkt zonder internetverbinding. De ingevoerde wissels worden lokaal in de browser bewaard.

## Bestanden

- index.html — de volledige app
- manifest.webmanifest — app-naam, kleuren en icoon van Jack
- sw.js — zorgt voor offline gebruik en installeerbaarheid
- README.md — deze uitleg

De drie eerste bestanden horen samen in dezelfde map en met dezelfde namen.

## Hoe het telt

- 's Morgens (voor 10u): de wisseldag telt voor wie Jack die dag krijgt.
- Overdag (rond 14-16u): de wisseldag telt voor niemand.
- 's Avonds (vanaf 20u): de wisseldag telt voor wie Jack afgeeft; de ontvanger begint de dag erna.

Een positief getal betekent dagen tegoed, een negatief getal dagen te veel gehad, nul is evenwicht.

## Online zetten via GitHub Pages

1. Maak een account op github.com als je er nog geen hebt.
2. Klik rechtsboven op de plus en kies New repository. Geef ze een naam, bijvoorbeeld wheres-jack, zet ze op Public en klik Create repository.
3. Klik op Add file en dan Upload files. Sleep index.html, manifest.webmanifest, sw.js en README.md erin en klik onderaan Commit changes.
4. Ga naar Settings, dan Pages. Kies bij Source de optie Deploy from a branch, selecteer branch main en map root, en klik Save.
5. Wacht ongeveer een minuut. Bovenaan die Pages-pagina verschijnt je adres, in de vorm https://JOUWNAAM.github.io/wheres-jack/

## Installeren op je iPhone

Open dat adres in Safari. Tik onderaan op het deelicoon en kies Zet op beginscherm. Where's Jack? verschijnt dan als een app met Jack als icoon en opent schermvullend, zonder browserbalk.

Op Android open je het adres in Chrome. Daar verschijnt vanzelf de melding App installeren, of je vindt ze in het menu rechtsboven.

## Iets aanpassen

Wil je later iets wijzigen, open dan het bestand in de repository, klik op het potlood om te bewerken, en commit de wijziging. GitHub Pages werkt zichzelf dan vanzelf bij.
