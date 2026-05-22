# Zwemvereniging Hartelust

Een statische, eenvoudige website voor [Zwemvereniging Hartelust](https://www.unieksporten.nl/sportaanbieder/2503/zv-hartelust/4172/zwemmen) — een vereniging voor aangepast zwemmen voor hart- en vaatpatiënten en mensen met Familiaire Hypercholesterolemie (FH) in Oostelijk West-Friesland.

## Structuur

```
index.html        Alle content (één lange pagina, Nederlands)
styles.css        Alle styling
assets/           Favicon en andere afbeeldingen
.nojekyll         GitHub Pages: sla Jekyll-verwerking over
```

## Lokaal bekijken

Open `index.html` direct in een browser, of serveer de map:

```sh
python3 -m http.server 8000
# bezoek http://localhost:8000
```

## Content aanpassen

Alle tekst staat in `index.html`. Secties zijn duidelijk gemarkeerd
(`<section id="...">`). Pas tekst, namen, of contactgegevens daar direct aan.
Kleuren en typografie staan bovenaan `styles.css` als CSS custom properties.

## Publicatie

De site wordt gepubliceerd via GitHub Pages vanuit de `main`-branch op de root.
Wijzigingen pushen naar `main` triggert automatisch een redeploy.

## Bronnen

De inhoud is samengesteld op basis van publiek beschikbare informatie:

- [unieksporten.nl — ZV Hartelust](https://www.unieksporten.nl/sportaanbieder/2503/zv-hartelust/4172/zwemmen)
- [Rodi.nl — Zwemvereniging Hartelust viert jubileum](https://www.rodi.nl/enkhuizen/nieuws/387291/zwemvereniging-hartelus-viert-jubileum)
