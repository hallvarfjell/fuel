# Endurance Fuel Planner

Installasjonsfri PWA for planlegging av karbohydrat, væske og elektrolytter for enkeltøkter, brick og triatlon.

## Starte lokalt
PWA-funksjoner krever HTTP/HTTPS. I mappen kan du for eksempel kjøre `python3 -m http.server 8080` og åpne `http://localhost:8080`. Vanlig bruk kan også testes ved å åpne `index.html`, men service worker/installasjon vil da ikke virke.

## Publisere
Last opp alle filene uendret til roten av et GitHub Pages-repository eller annen HTTPS-webserver.

## Modell
- Energi: MET × 3,5 × kg / 200 × minutter.
- Karbohydratandel øker med intensitet og når 95 % ved 80 % og høyere.
- Bare valgt utnyttbar andel av startlageret vises som tilgjengelig.
- Inntak går via en opptakskø begrenset av brukerens g/t-verdi.
- Væske og natrium bruker individuell svetterate, natriumkonsentrasjon, temperaturjustering og ønsket erstatningsgrad.

Dette er estimater og må testes individuelt.
