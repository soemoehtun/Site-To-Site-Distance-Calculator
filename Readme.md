# Geospatial Analysis & Visualization Tools

A collection of professional-grade, standalone web applications for geospatial data analysis, point visualization, and distance calculations. These tools are built as single-file HTML applications, making them easy to deploy and use without any installation or build steps.

## 🛠 Included Tools

### 1. Point File Creator Pro
**Filename**: `Poin-File-Creation-Tools.html`

A high-performance visualization tool for mapping individual points from tabular data.

- **Data Support**: Upload CSV or Excel files via drag-and-drop.
- **Dynamic Mapping**: Map any column to Latitude, Longitude, and Site Names.
- **Visual Customization**:
    - **Marker Shapes**: Pin, Circle, Square, Triangle, Diamond.
    - **Color Modes**: Universal single color or dynamic categorization based on data columns.
    - **Opacity & Size**: Fine-tune marker appearance for dense datasets.
- **Interactive Legend**: Automatically generates a count-based legend for categorical data.
- **Popup Customization**: Choose which data columns appear in information popups.
- **Multiple Map Layers**: Switch between Light, Dark, Satellite, Terrain, and OpenStreetMap views.

### 2. Site-to-Site Distance Calculator
**Filename**: `Site-to-Site-Distance-Calculator.html`

A specialized spatial analysis tool for calculating distances between points and identifying nearest neighbors.

- **Distance Logic**: Uses the **Haversine Formula** for accurate spherical distance calculations.
- **N-Nearest Neighbors**: Automatically finds and connects the $N$ closest sites for any selected point.
- **Interactive Map**:
    - Visualizes connections with customizable lines and markers.
    - Recenter and zoom to specific clusters or the entire dataset.
- **Data Table View**: Synchronized table showing all calculated distances and site details.
- **Export Options**: Export analysis results to GeoJSON, KML, or Excel for further professional use.
- **Visual Feedback**: Hover over sites to highlight their connections; click a site to focus on its local network.

## 🚀 Getting Started

No installation is required. These tools are completely portable.

1.  Download or clone the files to your local machine.
2.  Open any `.html` file in a modern web browser (Chrome, Edge, Firefox, or Safari).
3.  Upload your data file (CSV or XLSX) and start analyzing.

## 💻 Tech Stack

These applications are built using modern web standards for maximum compatibility and performance:
- **Core**: HTML5, React 18 (via CDN), Babel Standalone.
- **Styling**: Vanilla CSS (Modern UI/UX).
- **Mapping**: Leaflet.js 1.9.4.
- **Data Parsing**: PapaParse (CSV), SheetJS (Excel).
- **Icons**: Lucide/SVG Icons.

## 📝 Usage Notes

- **Browser Performance**: Designed to handle thousands of points efficiently on the client side.
- **Privacy**: All data processing is done locally in your browser. No data is uploaded to any server.

---
*Created with focus on visual excellence and professional analysis.*

## 👨‍💻 Author

**Developed by Soe Moe Tun**  
[Portfolio: soemoehtun.github.io/profolio/](https://soemoehtun.github.io/profolio/)
