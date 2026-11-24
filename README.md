# Atlas of Nations — 64 Country Edition

A bilingual (Indonesian–English) global learning platform exploring national development.

## Contents
- 50 country profiles across Asia, Europe, Africa, the Americas, and Oceania.
- Interactive world map; select a profiled country to open its dossier.
- Search, regional filter, HDI sorting, bilingual interface, dark mode, and reader font controls.
- Six learning chapters and research-method notes.
- Responsive layout for desktop, tablet, and mobile.

## Publish on GitHub Pages
1. Extract this ZIP.
2. Upload `index.html`, `style.css`, `countries.js`, `app.js`, and this README to the root of a GitHub repository.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then save.
6. Wait for GitHub Pages to publish the site. The URL appears in Settings → Pages.

## Data notes
- HDI values refer to 2023 as published in UNDP Human Development Report 2025. Values are displayed to three decimals.
- Population figures are rounded contextual estimates for 2024, not live counters.
- Natural-resource, human-capital, economic, energy, infrastructure, and challenge descriptions are concise qualitative syntheses. They are not a substitute for country statistical releases and are not real-time data.
- A country profile may be updated as new official data become available. Avoid comparing values from different reference years without checking the source.

## Primary references
- UNDP Human Development Data Center: https://hdr.undp.org/data-center/country-insights
- UNDP Human Development Report 2025, Statistical Annex: https://hdr.undp.org/sites/default/files/2025_HDR/HDR25_Statistical_Annex_Tables_1-7.pdf
- World Bank World Development Indicators: https://data.worldbank.org/
- International Energy Agency: https://www.iea.org/

## Technical notes
- Leaflet and the basemap are loaded from public CDNs; the world GeoJSON is loaded from the `datasets/geo-countries` GitHub repository. Internet access is required for the interactive map.
- If the map service is unavailable, the country index and profiles remain usable.
- This project is static and can be hosted on GitHub Pages without a server or database.
