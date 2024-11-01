
# PHP Kaart van Roermond met Nominatim API en Leaflet

Dit project haalt de coördinaten van Roermond op via de Nominatim API van OpenStreetMap en toont een kaart met Leaflet.

## Inhoud

- **PHP-script**: Haalt de coördinaten van Roermond op en genereert een HTML-bestand met de kaart.
- **Map HTML-bestand**: Bevat de gegenereerde kaart die een marker toont op de locatie van Roermond.

## Vereisten

- Een webserver met PHP-ondersteuning (bijv. XAMPP, WAMP, MAMP).
- Internetverbinding om de Nominatim API en Leaflet.js te gebruiken.

## Installatie en Gebruik

1. Download of clone dit project.
2. Plaats de bestanden in de root van je PHP-server (bijv. `htdocs` in XAMPP).
3. Open de browser en navigeer naar het PHP-bestand (`index.php`).
4. Het script genereert een bestand `map.html` met een kaart van Roermond en toont een bevestiging in de browser.

## Code-uitleg

- **Nominatim API**: Wordt gebruikt om de coördinaten van Roermond te verkrijgen.
- **PHP cURL**: Haalt de JSON-data van de Nominatim API op en decodeert deze naar de latitude en longitude.
- **Leaflet.js**: Gebruikt om een interactieve kaart te tonen met de coördinaten die door de API zijn opgehaald.
- Het eindresultaat is een HTML-bestand met een kaart en een marker op de locatie van Roermond.

## Gebruikte bronnen

- [Nominatim API](https://nominatim.org/)
- [Leaflet.js](https://leafletjs.com/)
- [OpenStreetMap](https://www.openstreetmap.org/)
