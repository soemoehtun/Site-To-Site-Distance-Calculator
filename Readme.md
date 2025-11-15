# 🗺️ Site-to-Site Distance Calculator – User Guide

[← Back to Calculator](#)

---

## Overview
- Generates a **results table** with nearest sites and distances.  
- Exports a **KML file** for visualization in Google Earth or other GIS tools.

---

## Step 1: Prepare Your Data
- Supported file formats: **CSV** or **TXT**.  
- Required columns:  
  - **Site ID / Name**  
  - **Latitude**  
  - **Longitude**  

---

## Step 2: Upload Your File
- Click the **Upload** button or file area.  
- Select your **CSV** or **TXT** file.  
- Column selection will be enabled automatically.

---

## Step 3: Map Columns

| Tool Field       | Map To             |
|-----------------|------------------|
| Site Column      | Site ID / Name    |
| Latitude Column  | Latitude          |
| Longitude Column | Longitude         |

---

## Step 4: Set Nearest Sites Count
- Enter the number of nearest sites (**N**) for each site.  
- **Example:** Enter **3** to calculate the 3 closest sites per site.

---

## Step 5: Process & Export
- Click **Process & Export KML**.  
- Tool calculates distances using the **Haversine formula**.  
- Results table is displayed, and KML file is downloaded automatically.

---

## Step 6: View Results
- **Results Table:** Shows nearest sites and distances (km).  
- **KML File:** Can be opened in Google Earth or GIS software.

---

## Tips & Best Practices
- Ensure coordinates are valid numbers.  
- Keep headers consistent in CSV/TXT files.  
- For large datasets (>5000 sites), processing may be slower.  
- Use the KML file in Google Earth or compatible GIS software.
