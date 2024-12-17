# Jumlah Jamaah Haji Tahun 2023 Riau

This project visualizes the number of Hajj pilgrims (Jamaah Haji) from Riau in 2023 on an interactive map using Leaflet.js. The data is presented in a GeoJSON format and displayed with color-coded regions based on the number of Hajj pilgrims in each district of Riau.

## Features
- Interactive map to display the number of Hajj pilgrims in each district of Riau.
- Dynamic color coding based on the number of pilgrims.
- Hover effect to show the number of pilgrims in each district.
- Legends to help interpret the color coding.
- Multiple base layers available (e.g., Google Streets, CartoDB Light).

## Setup

### Prerequisites

- A modern web browser.
- Internet connection to load map tiles and GeoJSON data.

### Files

- `index.html`: The main HTML file containing the map and JavaScript code to display the data.
- `riau_kabkot.geojson`: The GeoJSON file containing the geographical data for the districts in Riau.

### Instructions

1. Download the repository or clone it using the following command:
   ```bash
   git clone https://github.com/muhammadkusuma/Jumlah-Jemaah-Haji.git
   ```

2. Open `index.html` in a web browser to view the map.

### Data Source

The data used in this project is sourced from:
- **Jumlah Jamaah Haji Tahun 2023 Riau** (Riau Province Statistics Bureau)
  - [BPS Riau](https://riau.bps.go.id/id/statistics-table/2/MTIxIzI=/jumlah-jemaah-haji.html)

### Technologies Used

- **Leaflet.js**: A JavaScript library for interactive maps.
- **GeoJSON**: Data format used for representing geographical features.
- **HTML/CSS/JavaScript**: Standard web technologies for building the map and its interactions.

## How it Works

1. The map is centered around Sukajadi, Riau, with a zoom level of 8.
2. Various tile layers (such as Google Streets and CartoDB) are available for selecting the background map.
3. GeoJSON data is loaded for Riau's districts, and each district is color-coded based on the number of pilgrims.
4. Hovering over a district displays the number of pilgrims in that region.
5. A legend is provided to explain the color scheme used for the number of pilgrims.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Leaflet.js](https://leafletjs.com/) for the interactive map functionality.
- [OpenStreetMap](https://www.openstreetmap.org/) for map data.
- [CartoDB](https://carto.com/) for additional map tiles.
