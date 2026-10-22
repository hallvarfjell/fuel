Innhold i pakken
index.html
styles.css
app.js
manifest.webmanifest
sw.js
icon.svg
README.md

Jeg har kontrollert JavaScript-syntaksen, manifestet, filstrukturen og at alle hovedmodulene finnes i pakken.

Dette er inkludert
Ernæringsstrategi
Standardverdier for halvmaraton i konkurransefart
Flere øktdeler for triatlon, brick og intervalløkter
Individuell varighet, intensitet og MET-verdi per øktdel
Beregning av:
totalt energiforbruk
estimert karbohydratforbruk
tilgjengelig glykogen
væsketap
natriumtap
Redigerbare verdier for:
kroppsvekt
glykogenlager
utnyttbar andel av glykogenlageret
maksimalt karbohydratopptak
svetterate
natriumkonsentrasjon i svette
temperatur
ønsket væskeerstatning

Artikkelen fra Norges idrettshøgskole beskriver at energiforbruk kan uttrykkes ved MET, at karbohydratandelen øker med intensiteten, og at nesten all energi kan komme fra glykogen og glukose ved arbeid rundt eller over terskel. Den beskriver også at bare en del av glykogenlageret normalt kan utnyttes før kraftig tretthetsutvikling. Disse prinsippene er innarbeidet i modellen.

Produktdatabase

Du kan legge inn egne produkter og verdier per porsjon:

karbohydrat
energi
væske
natrium
kalium
magnesium

Dermed kan du legge inn konkrete produkter fra for eksempel Maurten og Precision Fuel & Hydration basert på næringsdeklarasjonen.

Inntaksplan
Valgfritt tidspunkt for hvert inntak
Antall porsjoner
Automatisk forslag til inntaksplan
Markering av inntak i energigrafen
«Mage-/opptakskø»
Begrensning i maksimalt karbohydratopptak per time
Varsel dersom planen overstiger valgt kapasitet
Analyse

Grafen viser utviklingen i tilgjengelig karbohydrat gjennom økten, med:

grønn kurve for tilgjengelig lager
oransje markører for planlagte inntak
rød kritisk grense
beregnet restlager ved mål

PWA-en varsler blant annet om:

kritisk lavt karbohydratlager
mye karbohydrat igjen i opptakskøen
inntak over valgt absorpsjonskapasitet
væskeinntak som overstiger beregnet svettetap
betydelig avvik fra beregnet væske- eller natriumbehov
Separat døgnmodell

Døgnmodellen ligger som egen side og:

henter energiforbruket fra aktiv trenings- eller konkurranseplan
lar deg inkludere eller utelate den aktive planen
lar deg legge inn et ubegrenset antall hverdagsaktiviteter
bruker MET, varighet og kroppsvekt for hver aktivitet
inkluderer manuelt angitt hvileenergi/RMR
inkluderer justerbar termisk effekt av mat
viser en grafisk fordeling mellom:
hvileenergi
hverdagsaktivitet
trening
matens termiske effekt

Hvileenergien legges inn direkte. Dermed er ikke kjønn, alder eller én bestemt beregningsformel obligatorisk.
