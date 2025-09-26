# 🌍 Environmental Assessment
*A map-based system to analyze and improve environmental sustainability in construction projects.*  

## ✨ Introduction  
Our website promotes **environmental sustainability** through a **map-based interface** that collects user input and evaluates an area’s ecological health.  

It generates an **Environmental Sustainability Score (ESS)** considering:  
🌫️ Air Quality • 🏭 Pollution • 💧 Humidity • 🌳 Trees • 🌡️ Temperature • 🌬️ Wind • 🌱 Soil • 🏢 Buildings  

---

## 📊 Environmental Sustainability Score (ESS)  
The ESS report assigns a score **0 – 100**:  

- 🟥 **Low Scores (0–40):** Require urgent remedies.  
- 🟨 **Medium Scores (41–70):** Some improvements needed.  
- 🟩 **High Scores (71–100):** Sustainable and balanced.  

🔧 Remedies include:  
- 🌫️ Improve air quality  
- 🏭 Reduce pollution  
- 🌳 Increase greenery  

---

## 📑 Final Report & Mitigation Measures  
The report highlights:  
- **Environmental Aspects** affected by construction  
- **Mitigation Measures** to reduce negative impacts  

📄 Sample Reports:  
- [ESS Report](https://github.com/Jay-1409/Storage/blob/ca19018f0f0f54c1c1f5eb7a57b037a0b4e065fe/ESS_Report%20(6).pdf)  
- [Environmental Sustainability Report](https://github.com/Jay-1409/Storage/blob/bacf1ff2bfc9526685900996c717b15b4b9fa53f/Environmental_Sustainability_Report_(12)%5B1%5D.pdf)  

---

## 🧰 Tech Stack

### 🌐 Frontend
- **JavaScript (Vite)** — fast build tool for frontend  
- **Tailwind CSS** — utility-first styling  
- **PostCSS** — CSS transformations  
- **ESLint** — linting & code consistency  
- **Leaflet.js** — interactive maps for site selection  

### 🐍 Backend
- **Python** — core backend logic & models  
- **Pandas / NumPy** — data processing and analysis  
- **Matplotlib / Seaborn** — plotting and visualizations (`plotgraphs.py`)  
- **ReportLab / FPDF** — PDF report generation (`genFactoryReport.py`, `generateess.py`)  
- **Custom Environmental Models**:
  - `ess.py` — Environmental Sustainability Score calculations  
  - `earthquackmodel.py` — Earthquake risk modeling  
  - `floodmodel.py` — Flood risk modeling  
  - `geteaifactory.py` — AI-driven factory data extraction  
  - `imageGenerate.py` — Image generation for visualization  

### 📂 Data & Assets
- **Datasets** — stored in `/dataset`  
- **Models** — stored in `/models`  
- **Reports & Outputs**:
  - `Construction_and_ESS_Report.pdf`  
  - `Environmental_Sustainability_Report.pdf`  
- **Static Images**:
  - `marked_location_tile.png`  
  - `material_waste_plot.png`  

### ⚙️ Project Management & Build
- **npm / package.json** — dependency management for frontend  
- **vite.config.js** — frontend build configuration  
- **tailwind.config.js** — Tailwind customization  
- **postcss.config.js** — PostCSS configuration  
- **eslint.config.js** — code quality rules  


## 💻 Frontend Output  
The website generates:  

- ⛽ Fuel Emissions  
- 🏷️ Impact Category  
- 🧱 Material Usage  
- 🌍 Overall Impact  
- 🌫️ PM10 Emissions  
- 🔥 Total Emissions  

---

## 🛠️ Roadmap  
- 🌐 Additional browser support  
- 🔗 More third-party integrations
- 
---

## 🧭 User Interaction Flow  
1. **🗺️ Map Selection (Leaflet):**  
   - Choose a location on the map.  
   - View environmental conditions with ESS.  

2. **🏢 Building Type Selection:**  
   Options:  
   - 🏭 Factory  
   - 🏘️ Flat  
   - 🏚️ Tenement  
   - 🏬 Commercial Building  

---

## 📋 Data Collection Forms  
Each building type requires user-specific inputs:  

- 🏭 **Factory** → Floors, Depth, Fuel, Product  
- 🏘️ **Flat** → Floors, Depth, Number of Apartments  
- 🏚️ **Tenement** → Floors, Depth, Number of Vehicles  
- 🏬 **Commercial Building** → Floors, Parking Depth, Stores, Vehicles  

---

## 🖼️ Screenshots / Demo  

- 🗺️ **Select Area**  
![App Screenshot](https://github.com/Jay-1409/Storage/blob/main/maps.png?raw=true)  

- 📊 **View Current Condition**  
![App Screenshot](https://github.com/Jay-1409/Storage/blob/main/curre.png?raw=true)  

- 🌍 **Environmental Changes After Construction**  
![App Screenshot](https://github.com/Jay-1409/Storage/blob/main/aftercons.png?raw=true)  

---

## 👨‍💻 Our Team  
| Member | GitHub | 
|--------|--------|
| **Raj Makwana** | [GitHub](https://github.com/raj_mistry01) |  
| **Het Modi** | [GitHub](https://github.com/say-het) |  
| **Krish Chothani** | [GitHub](https://github.com/KrishChothani) |  
| **Jay Shah** | [GitHub](https://github.com/Jay-1409) |  
| **Jainil Patel** | [GitHub](https://github.com/JainilPatel2502) |  

---
