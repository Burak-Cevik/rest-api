
# Kaart van Roermond met Leaflet

Dit project toont een kaart van Roermond met behulp van de Leaflet-bibliotheek en OpenStreetMap.

## Inhoud

- **HTML-bestand**: Bevat de Leaflet-kaartintegratie
- **Map**: Wordt weergegeven met een marker op de locatie van Roermond

## Vereisten

- Internetverbinding om externe bronnen (Leaflet CSS/JS) te laden
- Een moderne browser die JavaScript ondersteunt

## Installatie

1. Download of clone dit project.
2. Open het HTML-bestand (`index.html`) in een browser om de kaart van Roermond te bekijken.

## Code-uitleg

- **Leaflet.js**: Wordt gebruikt om een interactieve kaart te maken.
- De kaart wordt gecentreerd met `L.map().setView([latitude, longitude], zoom)`, waarbij coördinaten van Roermond worden ingevuld.
- **TileLayer**: Laadt de kaarttegels van OpenStreetMap.
- **Marker**: Voegt een marker toe op de locatie van Roermond, met een popup die de naam van de stad toont.

## Gebruikte bronnen

- [Leaflet.js](https://leafletjs.com/)
- [OpenStreetMap](https://www.openstreetmap.org/)
