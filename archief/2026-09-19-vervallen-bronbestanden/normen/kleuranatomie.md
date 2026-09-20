# Kleuranatomie

Elk merk voert dezelfde opbouw van negen tot tien rollen.

1. **Primair**: het donkere anker.
2. **Secundair**: de heldere merkkleur.
3. **Tertiair**: optioneel. Alleen SFP, CVD, SLB en FL hebben er een. Wit kan die rol vullen: bij FL is wit tertiair, bij SLB secundair. Waar wit de basis draagt is het een volwaardige hoofdkleur, geen restwaarde.
4. **Links en knoppen**: altijd een warm oranjerood, zonder uitzondering.
5. **Hover**: een lichtere versie van rol 4.
6 tot 8. **Drie tinten**, altijd afgeleid van de eigen hoofdkleuren, aflopend naar bijna wit.
9. **Wit**.
10. **Bodykleur**: #575757, behalve SFP en FL die zwart voeren.

## De tintbanden

Gemeten in L*, perceptuele lichtheid van 0 tot 100.

| Tint | Band |
|---|---|
| Tint 1 | L* 80 tot 86 |
| Tint 2 | L* 91 tot 96 |
| Tint 3 | L* 97 tot 99 |

Meet nooit in procent wit per kanaal. Die maat is misleidend bij geel, omdat het blauwkanaal daar bij nul begint en de uitkomst domineert.

Een hoofdkleur die zelf boven L*86 ligt kan geen tint 1 leveren. FL's geel zit op L*88.3 en heeft daarom geen tint 1. CVD en DGA vullen hun tint 1 met een andere hue, omdat hun geel ook te licht is.

## Twee harde regels

- Geen enkel merk voert een grijs vlak. Grijs bestaat uitsluitend als bodytekst. Randen en lijnen komen uit de merkkleuren of uit de primaire kleur met transparantie.
- De knopkleur is nooit een hoofdkleur. Uitzondering: SFP, waar de warme kleur zelf het merk is.

## Knoppen

Radius 3 px op FL, SLB en SwS. Radius 0 px op de vijf netwerksites. Primaire en secundaire knoppen renderen even groot: gelijke padding, minimumhoogte, lettergrootte en radius.

## Waar de kleuren live staan

Astra bewaart de global colors op twee plekken: `astra-settings[global-color-palette]` rendert de front-end, `astra-color-palettes[currentPalette]` vult de paletkiezer. Zet je er programmatisch maar een, dan kan Astra bij een volgende save je goede palet overschrijven met het oude. Zet ze altijd samen.
