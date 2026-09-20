# Logo-systeem

## Types

| Code | Type |
|---|---|
| A | logo: icoon plus wordmark |
| B | icoon |
| C | favicon |
| D | partnerlogo, eigenaarslogo of logoslogan, afhankelijk van het merk |
| E | tegel: vierkante social-avatar |

De regel onder de wordmark bij type D staat **altijd in hoofdletters**. Per merk luidt hij anders: "Partner van School for Professionals" bij de vier NL-labels, "Parceiro do School for Professionals" bij FL, "Partner of School for Professionals" bij SwS, "Eigenaar van School for Professionals" bij SLB. SFP voert zijn eigen slogan.

## Versies

| Code | Versie | Bedoeld voor |
|---|---|---|
| A | origineel | lichte achtergrond |
| B | alternatief 1 | het donkere anker |
| C | alternatief 2 | de merkkleur |

Het artwork wordt per versie verkleurd. Vallen twee versies samen omdat ze dezelfde inkt voeren, dan mag dat: SFP's alternatief 1 en 2 zijn identiek, alleen de grond verschilt.

## Twee leveringen

- **Transparant**: het artwork op transparant, in `svg/` en `png/`. Dit is de primaire set.
- **Met achtergrond**: elke versie op zijn eigen kleurgrond, dekkend, in `svg-op-kleur/` en `png-op-kleur/`.

Tegels zijn van nature dekkend en staan alleen in de transparante mappen.

## Formaten

SVG en PNG. WEBP is per 19 september 2026 vervallen: Imagify converteert op de sites zelf, dus een PNG volstaat als upload.

## Naamgeving

`{code}-{merk}-{typenaam}-{versienaam}.{ext}`, bijvoorbeeld `ab-de-presenteerschool-logo-alternatief-1.svg`. Alles in kleine letters met koppeltekens, zodat een raw-URL geen spaties bevat.

## Eisen aan het bestand

De SVG's bevatten echte vectorpaden. Geen ingebedde bitmaps, geen maskerlagen, geen afhankelijkheid van een geïnstalleerd lettertype: wordmarks staan als paden in het bestand. Kleuren zijn exact de merkhex uit `brand.json`.
