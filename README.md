# Dårlig Sikt

# Innholdsfortegnelse

- [Universell utfomring](#univsersell-utforming)
- [1. Kontrast](#1-kontrast)
- [2. Kartlegging av WCAG 2.1 krav](#2-kartlegging-av-wcag-21-krav)
- [3. Universell utformet](#3-universell-utformet)
- [Overblikk over funksjonalitet](#overblikk-over-funksjonalitet)
- [1. Hjermskjerm](#1-hjermskjerm)
- [2. Korttidsvarsel](#2-korttidsvarsel)
- [3. Langtidsvarsel](#3-langtidsvarsel)
- [4. Instillinger](#4-instillinger)
- [5. Favoritter](#5-favoritter)

Dårlig sikt er en værapplikasjon utvilket i et emnet ved UiO i samarbeid med MET (Metrologisk Institutt). Jeg, sammen med 5 andre, utviklet appen i henhold til casen "Case 3. Værvarsel for svaksynte" (https://in2000.met.no/2023/3-svaksynte). Vi jobbet smidig etter beste evne (scrum + kanban) gjennom et semester. Vi valgte denne casen fordi vi ville lære mer om, og ha litt mer praktisk utvikling, med hensyn til universell utforming.  

<img src="bilder/logo.png" style="display: block; margin: 0 auto;" alt="logo" width="300">

## Univsersell utforming

Universell utforming har vært et hovedfokus gjennom hele utviklingen. Den har bestått i hovedsak av følgende deler:

### 1. Kontrast

Vi bruke en kontrastskjekker til å tilpasse fargene til WCAG 2.1 kravene.

<img src="bilder/kontrastsjekker.png" alt="kontrastsjekker" width="300">

Vi endte opp med følgende fargetema:

<img src="bilder/våre-farger-og-yr-sine-farger.png" alt="våre farger og yr sine farger" width="300">

Og lagde i den forbindelse helt egne ikoner:

<img src="bilder/ikoner.png" alt="ikoner" width="300">

### 2. Kartlegging av WCAG 2.1 krav

Vi gikk systematisk gjennom alle WCAG 2.1 kravene og prøvde etter beste evne å innføre kravet.

<img src="bilder/uu-oversikt-de1.png" alt="universell utforming oversikt de1" width="300">
<img src="bilder/uu-oversikt-de2.png" alt="universell utforming oversikt de2" width="300">

### 3. Universell utformet 

Vi endte opp med følgende endringer etter at vi tok hensyn til universell utforming og WCAG 2.1 kravene.

<img src="bilder/universell-utforming-for-etter.png" alt="universell utforming før og etter" width="300">

## Overblikk over funksjonalitet

Dårlig sikt er full fungerende med Android sin talkback funksjon og har følgende funksjonaliteter. 

### 1. Hjermskjerm

Brukeren kan velge om å gi samtykke til posisjonen sin eller ikke. Stedsnavn vil enten være "Aker brygger" eller nåværende posisjon.

<img src="bilder/hjemskjerm.png" alt="hjemskjerm" width="300">

### 2. Korttidsvarsel

Her vil brukeren få et korttidsværvarsel. 

<img src="bilder/korttidsvarsel.png" alt="korttidsvarsel" width="300">

### 3. Langtidsvarsel

Her vil brukeren få et langtidsværvarsel. 

<img src="bilder/langtidsvarsel.png" alt="langtidsvarsel" width="300">

### 4. Instillinger

Her vil brukeren få muligheten til å velge mellom 1. celsius eller fahrenheit og 2. skriftstørrelse. 

<img src="bilder/instillinger.png" alt="instillinger" width="300">

I forbindelse med at en bruker kan ha ulik tekststørrelse har vi lagt inn tekst overflow. Hvis teksten blir for stor vil teksten bryte og endre layouten. Applikasjonen tilpasser seg dermed skjermstørrelse.

<img src="bilder/text-overflow.png" alt="tekst overflow" width="300">

### 5. Favoritter

Her vil brukeren få muligheten til å velge ulike favoritter. 

<img src="bilder/favoritter.png" alt="favoritter" width="300">
