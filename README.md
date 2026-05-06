# PM2.5 Air Quality Mapping and Heatmap Visualization

A mobile air quality monitoring and visualization project focused on analyzing the spatial and temporal variation of PM2.5 concentration and particle number concentration in Ponda, Goa using low-cost sensors, GPS tracking, and heatmap visualization techniques.

---

## Project Overview

Air pollution caused by fine particulate matter (PM2.5) has become a major environmental and public health concern. Traditional stationary monitoring systems often fail to capture local variations in pollution levels.

This project implements a **mobile air quality monitoring system** using:

- PMS5003 low-cost particulate matter sensors
- Arduino-based data acquisition
- GPS-enabled location tracking
- Heatmap and spatial visualization techniques
- Research-grade validation instruments

The system was mounted on a moving vehicle to collect real-time PM2.5 and particle number concentration data across different regions of Ponda, Goa.

The collected data was analyzed and visualized using Python to identify pollution hotspots and study the influence of:
- Traffic density
- Population density
- Land-use variation
- Human activities
- Weekday vs weekend effects

---

## Objectives

- Measure real-time PM2.5 concentration
- Measure particle number concentration
- Perform vehicle-based mobile monitoring
- Analyze spatial variation of air pollution
- Compare weekday and weekend pollution levels
- Generate heatmaps for pollution hotspot identification
- Study particle size distribution

---

## Technologies & Tools Used

### Hardware
- PMS5003 PM Sensor
- Arduino Microcontroller
- GPS Module
- Power Bank
- Vehicle-mounted monitoring setup

### Research Grade Instruments
- DustTrak DRX
- Optical Particle Sizer (OPS)

### Software & Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Folium
- OpenStreetMap
- Google Colab

---

## Project Workflow

1. Collect real-time PM2.5 data using PMS5003 sensors
2. Record GPS coordinates simultaneously
3. Store collected data in CSV format
4. Process and clean data using Python
5. Generate spatial heatmaps and graphs
6. Analyze weekday vs weekend variations
7. Compare concentration across different regions

---

## Study Area

The monitoring campaign was conducted in:

**Ponda, Goa, India**

The study covered:
- Residential areas
- Traffic-dominated regions
- Forest regions
- Village areas
- Campus surroundings

---

## Data Collection Strategy

- Monitoring conducted during both:
  - Morning sessions
  - Evening sessions

- Average monitoring duration:
  - ~1 hour 45 minutes per session

- Data collected using a vehicle-mounted mobile setup

---

## Features

- Real-time PM2.5 monitoring
- GPS-based spatial mapping
- Heatmap visualization
- Mobile monitoring setup
- Particle number concentration analysis
- Multi-location comparison
- Weekday vs weekend comparison
- Fine particle distribution analysis

---

## Repository Structure

```bash
├── Heatmap_Plot.ipynb
├── final_drone_pm_data.csv
├── Data for analysis NC graphs.xlsx
├── README.md
```

---

## Results

### Key Findings

- Higher PM2.5 concentrations observed in:
  - Traffic-heavy areas
  - Urban regions
  - Densely populated zones

- Lower concentrations observed in:
  - Forest areas
  - Vegetated regions
  - Less congested locations

- Weekdays showed higher pollution levels compared to weekends.

- Fine particles (0.3–1 µm) dominated the ambient environment.

- Particle concentration decreased with increasing particle size.

---

## Heatmap Visualization

The project generates spatial heatmaps showing:
- Pollution hotspots
- Local PM2.5 variation
- Spatial pollution distribution

Heatmaps help identify:
- High exposure regions
- Traffic emission zones
- Urban pollution clusters

---

## Installation

### Clone Repository

```bash
git clone https://github.com/dhavalnikam/PM2.5-Air-Quality-Mapping-and-Heatmap-Visualization-.git
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib folium openpyxl
```

---

## Usage

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Heatmap_Plot.ipynb
```

Run all cells to:
- Process PM2.5 data
- Generate plots
- Create heatmaps

---

## Future Improvements

- IoT-based live monitoring dashboard
- Cloud database integration
- Real-time AQI prediction using Machine Learning
- Web-based GIS dashboard
- Multi-city monitoring expansion
- Sensor calibration enhancement

---

## Applications

- Smart city planning
- Environmental monitoring
- Urban pollution analysis
- Public health assessment
- Traffic pollution studies
- Air quality research

---

## Author

**Dhaval Nikam**  
B.Tech Project  
Indian Institute of Technology Goa

---

## References

1. Mobile monitoring of PM2.5 and exposure assessment in urban environments
2. Advances in low-cost air quality monitoring
3. Mobile monitoring of air pollution reveals spatial and temporal variability

---

## License

This project is developed for academic and research purposes.
