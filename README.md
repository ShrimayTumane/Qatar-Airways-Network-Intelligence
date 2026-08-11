# ✈️ Qatar Airways Global Network Intelligence

### Summer 2026 Route Network Analysis | Python • Pandas • Tableau

[![Tableau Public](https://img.shields.io/badge/Tableau%20Public-Live%20Demo-E97627?logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/shrimay.tumane/viz/Book1_17864051986490/QatarAirwaysNetworkIntelligence?publish=yes)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Tableau](https://img.shields.io/badge/Tableau-Data%20Visualization-E97627?logo=tableau&logoColor=white)](https://www.tableau.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE) <!-- TODO: confirm license type -->

---

## 🚀 Live Demo

**[👉 Launch the Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/shrimay.tumane/viz/Book1_17864051986490/QatarAirwaysNetworkIntelligence?publish=yes)**

Explore the full route network, filter by region and route type, and drill into individual KPIs — no download required.

<p align="center">
  <a href="https://public.tableau.com/app/profile/shrimay.tumane/viz/Book1_17864051986490/QatarAirwaysNetworkIntelligence?publish=yes">
    <img src="screenshots/dashboard.png" alt="Qatar Airways Global Network Intelligence Dashboard Preview" width="100%">
  </a>
</p>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Business Objective](#-business-objective)
- [Key Features](#-key-features)
- [Live Demo](#-live-demo)
- [Key Metrics](#-key-metrics)
- [Regional Exposure](#-regional-exposure)
- [Route Mix](#-route-mix)
- [Analytical Questions Answered](#-analytical-questions-answered)
- [Tech Stack](#-tech-stack)
- [Analytical Workflow](#-analytical-workflow)
- [Project Structure](#-project-structure)
- [Getting Started](#️-getting-started)
- [Key Insights](#-key-insights)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)
- [License](#-license)

## 🚀 Live Demo

- Interactive dashboard: [Tableau Public Live Demo](https://public.tableau.com/app/profile/shrimay.tumane/viz/Book1_17864051986490/QatarAirwaysNetworkIntelligence?publish=yes)
- GitHub repository: [Qatar Airways Network Intelligence](https://github.com/ShrimayTumane/Qatar-Airways-Network-Intelligence)

## 🧭 Portfolio Highlight

This project demonstrates end-to-end analytics and storytelling for an aviation network strategy problem. It combines data cleaning, geographic analysis, route classification, and executive-friendly dashboard design to transform raw route data into network intelligence.

---

## 📊 Project Overview

This project analyzes the **Qatar Airways Summer 2026 global route network** to understand the airline's geographic reach, regional exposure, route structure, and long-haul network positioning.

It combines **Python-based data preparation and analysis** with an interactive **Tableau dashboard** designed as a network intelligence report — rather than focusing on individual routes, the analysis looks at the network from a strategic perspective:

- Where is Qatar Airways most geographically exposed?
- How diversified is the network across regions?
- What proportion of routes are long-haul?
- How extensive is the global destination footprint?
- What does the route mix reveal about network strategy?
- How does Doha function as the central network hub?

---

## 🎯 Business Objective

The objective is to transform raw route-level data into actionable network intelligence, giving a high-level, executive-ready view of the airline's global network scale and structure — the kind of summary a network strategy or route planning team would use to spot concentration risk and expansion opportunity at a glance.

---

## ✨ Key Features

- 🗺️ **Interactive global route map** — every route from the Doha hub visualized by origin/destination geography
- 📌 **Five headline KPI cards** — destinations, countries, regions, average distance, long-haul share
- 🌍 **Regional exposure breakdown** — destination count by region, sortable and filterable
- 🛫 **Route classification** — routes segmented into short-, medium-, long-, and ultra-long-haul
- 🎨 **Branded, presentation-ready design** — styled to communicate findings like a network strategy report, not a raw data dump
- 🔍 **Drill-down filtering** — explore by region and route type directly in the live dashboard

---

## 📈 Key Metrics

| Metric | Value |
|---|---:|
| Destinations | **149** |
| Countries | **77** |
| Regions | **6** |
| Average Route Distance | **5,343 km** |
| Long-Haul Share | **21.5%** |

---

## 🌍 Regional Exposure

Regional exposure shows how the destination network is distributed geographically.

| Region | Destinations |
|---|---:|
| Asia-Pacific | **50** |
| Europe | **41** |
| Africa | **25** |
| Americas | **17** |
| Middle East | **10** |
| Caucasus & Central Asia | **5** |

**Key Insight:** The network is heavily concentrated in **Asia-Pacific and Europe**, which together account for the majority of destinations. This suggests Qatar Airways' network strategy is strongly anchored around connectivity between Doha and major markets across Asia and Europe, while maintaining meaningful — but comparatively smaller — exposure to Africa and the Americas.

---

## 🛫 Route Mix

The route mix breaks down the network by distance classification.

| Route Type | Routes | Share |
|---|---:|---:|
| Medium-haul | **77** | **51.68%** |
| Long-haul | **32** | **21.48%** |
| Short-haul | **30** | **20.13%** |
| Ultra-long-haul | **10** | **6.71%** |

**Key Insight:** Medium-haul routes make up roughly **52%** of the network, while long-haul and ultra-long-haul routes combined represent about **28%** — underscoring the importance of long-distance connectivity to Qatar Airways' overall network strategy.

---

## 🔎 Analytical Questions Answered

<details>
<summary><strong>Network Scale</strong></summary>

- How large is the global destination footprint?
- How many countries are connected?
- How geographically diversified is the network?
</details>

<details>
<summary><strong>Regional Strategy</strong></summary>

- Which regions receive the greatest network exposure?
- Which regions are comparatively underrepresented?
- Is the network geographically concentrated?
</details>

<details>
<summary><strong>Route Strategy</strong></summary>

- What is the distribution of short-, medium-, long-, and ultra-long-haul routes?
- How significant is long-haul connectivity?
- What does route distance tell us about network positioning?
</details>

<details>
<summary><strong>Hub Strategy</strong></summary>

- How does Doha function as the central network hub?
- Which geographic markets are most strongly connected to Doha?
- Where does the network extend most aggressively?
</details>

---

## 🧰 Tech Stack

| Category | Tools |
|---|---|
| **Data Analysis** | Python, Pandas, NumPy |
| **Data Visualization** | Tableau, Tableau Public |
| **Data Preparation** | CSV, data cleaning, feature engineering, geographic coordinate processing, route classification |

---

## 🧠 Analytical Workflow

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

---

## 📂 Project Structure

<!-- TODO: confirm this matches your actual repo layout -->
```text
qatar-airways-network-intelligence/
├── data/
│   ├── raw/                  # Original route dataset
│   └── processed/            # Cleaned, feature-engineered data
├── notebooks/                # Exploratory analysis notebooks
├── scripts/                  # Data cleaning & feature engineering scripts
├── screenshots/
│   └── dashboard.png         # Dashboard preview image
├── README.md
└── requirements.txt
```

---

## ⚙️ Getting Started

<!-- TODO: fill in exact commands once scripts/notebooks are finalized -->

```bash
# Clone the repository
git clone https://github.com/ShrimayTumane/qatar-airways-network-intelligence.git
cd qatar-airways-network-intelligence

# Install dependencies
pip install -r requirements.txt

# Run the data preparation pipeline
python scripts/prepare_data.py
```

Once the processed dataset is generated, open `Book1.twbx` in Tableau Desktop (or view it directly via the [Live Demo](#-live-demo)) to explore the dashboard interactively.

---

## 💡 Key Insights

- Qatar Airways' Summer 2026 network spans **149 destinations across 77 countries and 6 regions**, reflecting a genuinely global footprint anchored at the Doha hub.
- **Asia-Pacific and Europe dominate regional exposure**, together accounting for the majority of destinations — consistent with Doha's positioning as a bridge between Western and Eastern markets.
- **Medium-haul routes are the backbone of the network** (~52%), while long-haul and ultra-long-haul routes (~28% combined) reflect a deliberate strategy to sustain Doha's role as a long-distance connecting hub.
- An average route distance of **5,343 km** reinforces the network's long-distance, hub-and-spoke character rather than a regional point-to-point model.

---

## 🔮 Future Enhancements

- [ ] Incorporate fare/pricing data to analyze route profitability alongside network reach
- [ ] Add historical seasons (Winter 2025, Summer 2025) for year-over-year network comparison
- [ ] Layer in on-time performance or flight frequency data per route
- [ ] Build a predictive model for potential new route demand
- [ ] Add competitor network overlays (Emirates, Etihad) for benchmarking

---

## 👤 Author

**Shrimay Tumane**

[![GitHub](https://img.shields.io/badge/GitHub-ShrimayTumane-181717?logo=github&logoColor=white)](https://github.com/ShrimayTumane)
<!-- TODO: add LinkedIn / portfolio badges -->
<!-- [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL) -->
<!-- [![Portfolio](https://img.shields.io/badge/Portfolio-Visit-6C3EF4)](YOUR_PORTFOLIO_URL) -->

---

## 📄 License

<!-- TODO: confirm license choice -->
This project is licensed under the [MIT License](LICENSE).
