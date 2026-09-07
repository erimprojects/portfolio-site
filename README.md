# Portfolio - Erim Kocak

Persoonlijke portfoliosite voor het vak WPFW (De Haagse Hogeschool), opdracht 1.
Statische site, gebouwd met semantische HTML5 en responsive CSS3, zonder framework.

## Structuur

```
portfolio/
├── index.html        Whoami - wie ik ben en waar ik mee werk
├── projecten.html    Overzicht van projecten
├── blog.html         Overzicht van blogposts
├── css/
│   └── style.css     Alle styling (mobile first)
├── images/           Afbeeldingen, o.a. de profielfoto
├── projecten/        Ruimte voor losse projectpagina's
└── blog/             Ruimte voor losse blogposts
```

## Uitbreiden

- **Nieuw project**: kopieer een `<article class="kaart">`-blok in `projecten.html` en pas de inhoud aan.
- **Nieuwe blogpost**: kopieer een `<article class="post">`-blok in `blog.html`; zet de juiste datum in `datetime="JJJJ-MM-DD"`.
- **Detailpagina**: maak een bestand in `projecten/` of `blog/` en verwijs ernaar vanaf het overzicht.

## Breekpunten

| Scherm  | Breedte      | Layout                          |
|---------|--------------|---------------------------------|
| Mobiel  | tot 480px    | Eén kolom, nav onder het logo   |
| Tablet  | vanaf 768px  | Twee kolommen, nav naast logo   |
| Desktop | vanaf 1024px | Drie kolommen, meer witruimte   |

## Lokaal bekijken

Open `index.html` in de browser, of start een lokale server:

```bash
python3 -m http.server 8000
```

## Nog te doen

- Eigen profielfoto plaatsen in `images/` (vervangt `profielfoto.svg`) en het `alt`-attribuut controleren.
- Blogposts uitwerken en de `href="#"`-links vervangen door echte detailpagina's.
