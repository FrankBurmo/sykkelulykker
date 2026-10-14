# Sykkelulykker

Interaktivt kart over ulykkesclustre for sykkelulykker. Kartet viser
clustre av ulykkessteder med mindre enn 20 meters avstand, ikke én markør
for hver enkelt ulykke. Datasettet i kartet inneholder 2 084 clustre fra
109 kommuner, med 6 320 ulykker til sammen. Siste registrerte ulykkesår
i materialet er 2025.

## Dette viser kartet

Hvert punkt er et ulykkescluster. Sirkelstørrelsen viser antall ulykker,
og fargen kan vise antall eller trend. Klikk på et punkt for å se kommune,
antall involverte enheter, avstand fra clusterets senter, trend,
utvikling over tid, siste ulykkesår, trafikanttyper og eventuelle
vegreferanser.

Kartet kan filtreres på:

- **Sesong:** hele året, vinter, vår, sommer eller høst.
- **Farge:** antall ulykker, trend eller trend relativt til alle.
- **Clustre uten trend:** kan skjules.
- **Minste antall ulykker:** juster nedre grense for hvilke clustre som vises.

Velg mellom gråtone- og topografisk bakgrunnskart. Trendene og ulykkestallene
er forhåndsberegnet og ligger innebygd i `kart.html`. Kartet oppgir ikke
opprinnelig datakilde eller beregningsperioden for trendene.

## Åpne kartet

Åpne [kart.html](kart.html) i en nettleser. [index.html](index.html)
videresender til kartet. Bakgrunnskartene og Leaflet lastes fra eksterne
tjenester, så internettforbindelse er nødvendig.