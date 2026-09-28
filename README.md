# Orbit Atlas

A satellite globe for learning where the world's countries, India's states and union territories, and China's provinces and regions are.

**Live:** https://mtbgreg1.github.io/orbit-atlas/

- Explore: spin the globe, click or search any place.
- Find it / Name it quizzes with region filters, at three levels: Borders on, No borders, and Cities (capitals and major cities scored by distance, MapTap-style).
- Progress is saved in the browser, with optional sync to a secret GitHub Gist.

## Data and imagery

- Zoomed out: NASA Blue Marble (GIBS), public domain.
- Zoomed in: Sentinel-2 cloudless 2024 by EOX IT Services GmbH (contains modified Copernicus Sentinel data 2024), CC BY-NC-SA 4.0, or Esri World Imagery.
- Boundaries and cities: Natural Earth (public domain), showing de facto boundaries.
- Country details: mledoze/countries (ODbL).

Everything is in `index.html`, `geo.json` and `cities.json`. There is no build step.
