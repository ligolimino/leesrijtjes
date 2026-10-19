# Letterlab — leesrijtjes

Rijtjes woorden om luidop te lezen: klassikaal op het bord met een
aanwijzer, of afgedrukt als leesblad op A4. Je typt de woorden zelf, of de
tool zoekt ze met alleen de letters die de cursisten al kennen.

Stappenplan technisch lezen: stap 13 (leesrijtjes, wisselrijtjes) en 16.

## Mogelijkheden in de link

Zelf typen:

| In de link | Betekenis |
|---|---|
| `woorden=raam,maan,vaas\|kip,kim,vis` | Komma's tussen de woorden, een `\|` begint een nieuwe rij. |
| `mix=ja` | Door elkaar, met een knop voor een nieuwe volgorde. |

Vanzelf zoeken (uit de woordenlijst van het klik-klakboekje):

| In de link | Betekenis |
|---|---|
| `letters=r,aa,m,s,v,i,k` | De klanken die de cursisten kennen. |
| `vorm=mkm` | km, mk, mkm, mmkm, mkmm ... (meerdere met komma's). Standaard mkm. |
| `aantal=12` | Hoeveel woorden (2 tot 60). |
| `wissel=ja` | Wisselrijtje: telkens één klank anders (raak, maak, mik, tik ...). |
| `nonsens=ja` | Ook onbestaande woorden. |
| `uit=sik,mik` | Deze woorden nooit. |

Altijd:

| In de link | Betekenis |
|---|---|
| `kolommen=3` | Aantal kolommen (anders vanzelf). |
| `luister=ja` | Luisterknop voor het aangewezen woord. |
| `titel=Raam` | Titel bovenaan het afgedrukte leesblad. |

## Bediening

| Knop | Toets | Wat |
|---|---|---|
| tik op een woord | spatie, pijlen | aanwijzen; gelezen woorden worden lichter |
| luidspreker | L | het aangewezen woord beluisteren |
| klok | T | stopwatch starten en stoppen |
| pijltjes door elkaar | N | nieuwe woorden of een nieuwe volgorde |
| herstel | R | aanwijzer en stopwatch terug naar het begin |
| printer | | leesblad op A4 |

## Woordenlijst

De tool gebruikt `klikklak/wordlist-v1.js`, zodat aanpassingen aan de
woordenlijst van het klik-klakboekje ook hier gelden. Lukt dat niet, dan de
kopie `wordlist-v1.js` in deze repository (bron: OpenTaal, zie
`OPENTAAL-LICENSE.txt`). Een bestaand woord is niet altijd geschikt:
controleer de woorden en zet ongewenste woorden in `uit=`.

## Publiceren (eenmalig)

1. Maak bij **ligolimino** een openbare repository `leesrijtjes`.
2. Kies **uploading an existing file** en sleep de **inhoud** van deze map
   erin (niet de map zelf). Kies **Commit changes**.
3. **Settings → Pages**: branch `main`, map `/ (root)`, **Save**.
4. Na enkele minuten: `https://ligolimino.github.io/leesrijtjes/`.

Open je die link zonder iets erachter, dan zie je een uitlegpagina met een
formulier om zelf een link te maken.

## Zelfstandig en onderhoudsvrij

- Alleen gewone bestanden: geen installatie, geen bouwstap, geen databank.
- Het lettertype Andika staat in de repository zelf.
- De volledige oefening staat in de link. Een link blijft werken zolang de
  repository online staat.
- In Genially is de achtergrond doorzichtig, zodat de dia zichtbaar blijft.

## Na een wijziging

Telefoons kunnen een oude versie bewaren. Wacht even of herlaad de pagina.

## Licentie lettertype

Andika valt onder de SIL Open Font License, zie
`assets/fonts/OFL-LICENSE.txt`.
