# mesutbora.be

Portfoliopagina van Mesut Bora Nodli. Eén statische HTML-pagina, geen build, geen afhankelijkheden.

## Inhoud

    index.html        de pagina zelf
    cv.pdf            CV, gelinkt vanaf de downloadknop
    images/           screenshots van de projecten

## Lokaal bekijken

    python -m http.server 8000

Daarna http://localhost:8000 openen.

## Screenshots vervangen

De pagina verwacht deze bestandsnamen in `images/`:

    poolboy-1.png  poolboy-2.png  poolboy-3.png     staand, gsm-formaat
    bizgame-1.webp bizgame-2.png  bizgame-3.png  bizgame-4.png

Ontbreekt er een, dan toont de pagina een gestippeld kader met de bestandsnaam
in plaats van een kapotte afbeelding.
