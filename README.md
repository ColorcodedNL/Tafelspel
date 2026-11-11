# Tafelspel

Een speels oefenspel voor de tafels van 1 t/m 10, voor kinderen van groep 3/4 (ca. 6 tot 8 jaar). Eén HTML-bestand zonder dependencies dat direct in de browser werkt, ook op iPad en tablet.

**Live spelen:** [colorcodednl.github.io/Tafelspel](https://colorcodednl.github.io/Tafelspel/)

---

## Wat het doet

Het spel heeft drie onderdelen, in de volgorde waarin je een tafel leert:

### Tafels
Kies een tafel (1 t/m 10) en vul de hele tafel in, van `1 × 3` tot `10 × 3`. Tik een rij aan en typ het antwoord met het cijferpad. Een goed antwoord kleurt groen en je springt vanzelf naar de volgende rij. Als de hele tafel goed is volgt confetti.

### Oefenen
Losse sommen met hulp: elke som wordt getoond als rijen bolletjes, zodat je ziet wat vermenigvuldigen betekent. Kies een specifieke tafel of "Alle", en kies hoe je antwoordt:
- **Kiezen:** vier antwoordknoppen. De foute opties liggen dicht bij het goede antwoord (bijv. `7 × 3` geeft ook 18 en 24), zodat raden niet werkt.
- **Zelf typen:** antwoord intypen met het cijferpad. Fout is niet erg, je mag het opnieuw proberen.

Geen score, gewoon spelen.

### Overhoring
Geen hulp en geen bolletjes. Kies een tafel of "alle tafels door elkaar" en beantwoord 10 sommen met het cijferpad. Elke som komt één keer voor. Aan het eind zie je je score (bijv. 9 van 10) en een overzicht van wat goed en fout ging.

---

## Kenmerken

- Geen installatie, gewoon `index.html` openen
- Gemaakt voor iPad (staand en liggend), werkt ook op desktop
- Op desktop kun je ook typen met het toetsenbord (cijfers, Backspace, Enter)
- Eerlijke verdeling: alle sommen komen langs voordat er één dubbel komt (10 beurten bij één tafel, 100 bij alle tafels; 3 × 7 en 7 × 3 zijn aparte sommen), ook over meerdere rondes en dagen heen
- Onder de som zie je hoeveel sommen er nog in de zak zitten
- Een som komt nooit twee keer achter elkaar, ook niet bij de overgang naar een nieuwe ronde
- Als de zak leeg is, vliegen alle sommen er opnieuw in en wordt de zak geschud (korte animatie)
- Een antwoord kan niet met een 0 beginnen; het spel geeft dan een korte melding
- Confetti bij een goed antwoord of een complete tafel
- Speels design met het Fredoka-lettertype

---

## Gebruik

```bash
git clone https://github.com/ColorcodedNL/Tafelspel.git
open Tafelspel/index.html
```

Of speel direct online via GitHub Pages.

---

## Bestanden

- `index.html`: het volledige spel
- `tafelspel-favicon-32.png`, `tafelspel-favicon-192.png`, `tafelspel-apple-touch-icon.png`: pictogrammen

Het lettertype Fredoka laadt van Google Fonts. Zonder internet valt het spel terug op het systeemlettertype en blijft het gewoon werken.

---

## Achtergrond

Gemaakt voor mijn dochter om de tafels te oefenen op de iPad. De drie onderdelen sluiten aan bij de leerfases: eerst een tafel instuderen (Tafels), dan losse sommen oefenen met hulp (Oefenen) en tot slot jezelf testen (Overhoring).

---

## Licentie

MIT, gebruik en pas gerust aan.
