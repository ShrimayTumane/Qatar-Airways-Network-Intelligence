# ✈️ Qatar Airways Global Network Intelligence

### Summer 2026 Route Network Analysis | Python • Pandas • Tableau

[![Tableau Public](https://img.shields.io/badge/Tableau%20Public-View%20Dashboard-E97627?logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/shrimay.tumane/viz/Book1_17864051986490/QatarAirwaysNetworkIntelligence?publish=yes)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Tableau](https://img.shields.io/badge/Tableau-Data%20Visualization-E97627?logo=tableau&logoColor=white)](https://www.tableau.com/)

---

## 📊 Project Overview

This project analyzes the **Qatar Airways Summer 2026 global route network** to understand the airline's geographic reach, regional exposure, route structure, and long-haul network positioning.

The project combines **Python-based data preparation and analysis** with an interactive **Tableau dashboard** designed as a network intelligence report.

Rather than focusing only on individual routes, the analysis looks at the network from a strategic perspective:

- Where is Qatar Airways most geographically exposed?
- How diversified is the network across regions?
- What proportion of routes are long-haul?
- How extensive is the global destination footprint?
- What does the route mix reveal about network strategy?
- How does Doha function as the central network hub?

---

## 🎯 Business Objective

The objective is to transform raw route-level data into actionable network intelligence.

The dashboard provides a high-level view of:

| Metric | Value |
|---|---:|
| Destinations | **149** |
| Countries | **77** |
| Regions | **6** |
| Average Route Distance | **5,343 km** |
| Long-Haul Share | **21.5%** |

These metrics provide a compact view of the airline's global network scale and structure.

---

# 🗺️ Dashboard

## Qatar Airways Global Route Network

The primary visualization maps the global route network originating from the Doha hub.

The map highlights:

- Global destination connectivity
- Route density
- Regional reach
- Long-distance network coverage
- Route-type distribution

![Qatar Airways Global Network](screenshots/dashboard.png)

### Interactive Tableau Dashboard

👉 **[Open the interactive Tableau Public dashboard](https://public.tableau.com/app/profile/shrimay.tumane/viz/Book1_17864051986490/QatarAirwaysNetworkIntelligence?publish=yes)**

---

# 📈 Key Dashboard Components

## 1. Global Route Network

A geographic visualization of Qatar Airways' route network.

The visualization uses:

- Latitude / Longitude
- Route ID
- Path Order
- Route Type
- Origin and destination coordinates

The Doha hub acts as the central network node, with routes extending across Europe, Asia-Pacific, Africa, the Americas, the Middle East and Central Asia.

---

## 2. KPI Overview

The dashboard summarizes the network through five headline indicators:

### 149 Destinations

Represents the number of unique destinations included in the analyzed route network.

### 77 Countries

Shows the geographic breadth of the network across countries.

### 6 Regions

Measures the number of distinct geographic regions represented.

### 5,343 km Average Distance

Provides an indication of the typical geographic length of the network's routes.

### 21.5% Long-Haul Share

Measures the proportion of routes classified as long-haul.

---

# 🌍 Regional Exposure

Regional exposure shows how the destination network is distributed geographically.

Current network exposure:

| Region | Destinations |
|---|---:|
| Asia-Pacific | **50** |
| Europe | **41** |
| Africa | **25** |
| Americas | **17** |
| Middle East | **10** |
| Caucasus & Central Asia | **5** |

### Key Insight

The network is heavily concentrated in **Asia-Pacific and Europe**, which together account for the majority of destinations in the analyzed network.

This indicates that Qatar Airways' network strategy is strongly anchored around connectivity between Doha and major markets across Asia and Europe, while maintaining meaningful exposure to Africa and the Americas.

---

# 🛫 Route Mix

The route mix provides a breakdown of the network by route classification.

| Route Type | Routes | Share |
|---|---:|---:|
| Medium-haul | **77** | **51.68%** |
| Long-haul | **32** | **21.48%** |
| Short-haul | **30** | **20.13%** |
| Ultra-long-haul | **10** | **6.71%** |

### Key Insight

Medium-haul routes represent the largest portion of the analyzed network, accounting for approximately **52%** of routes.

Long-haul and ultra-long-haul routes together represent approximately **28%** of the network, highlighting the importance of Qatar Airways' long-distance connectivity strategy.

---

# 🔎 Analytical Questions

The project was designed around several business questions:

### Network Scale

- How large is the global destination footprint?
- How many countries are connected?
- How geographically diversified is the network?

### Regional Strategy

- Which regions receive the greatest network exposure?
- Which regions are comparatively underrepresented?
- Is the network geographically concentrated?

### Route Strategy

- What is the distribution of short-, medium-, long- and ultra-long-haul routes?
- How significant is long-haul connectivity?
- What does route distance tell us about network positioning?

### Hub Strategy

- How does Doha function as the central network hub?
- Which geographic markets are most strongly connected to Doha?
- Where does the network extend most aggressively?

---

# 🧰 Technology Stack

### Data Analysis

- Python
- Pandas
- NumPy

### Data Visualization

- Tableau
- Tableau Public

### Data Preparation

- CSV
- Data cleaning
- Feature engineering
- Geographic coordinate processing
- Route classification

---

# 🧠 Analytical Workflow

```text
Raw Route Data
      │
      ▼
Data Cleaning
      │
      ▼
Geographic Validation
      │
      ▼
Route Classification
      │
      ▼
Feature Engineering
      │
      ├── Route Type
      ├── Region
      ├── Distance
      ├── Route ID
      └── Path Order
      │
      ▼
Exploratory Analysis
      │
      ▼
Tableau Visualization
      │
      ▼
Network Intelligence Dashboard
```
