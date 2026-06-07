# 🍽️ Zomato Restaurants Analysis Dashboard

An interactive Power BI dashboard analyzing **50,000+ rows** and **17 columns** of Zomato restaurant data sourced from Kaggle. Built to uncover actionable insights on restaurant performance, cuisine trends, customer preferences, and location-based patterns across cities.

---

###  Features

- **Restaurant Type Filtering** — Explore across 7 types: Buffet, Cafes, Delivery, Desserts, Dine-out, Drinks & Nightlife, Pubs and Bars
- **Cuisine Slicer** — Filter by 10+ cuisine combinations including Biryani, North Indian, Chinese, Continental, and more
- **Location Slicer** — Drill down by neighborhood/area (Banashankari, BTM, Brigade Road, and many more)
- **Online Order & Table Booking Filters** — Yes/No slicers to segment restaurants by service type
- **KPI Cards** — Instant view of Avg Rating, Total Votes, and Avg Bill Amount
- **Top 10 Restaurants Chart** — Bar chart ranking restaurants by total votes/performance
- **Donut Chart** — Restaurants By Type distribution with 8+ segments
- **Gauge Chart** — Avg Bill Amount visualization from 0.00K to 2.00K

---

###  Screenshots

Dashboard View

<img width="1638" height="908" alt="Zomato-restaurant-analysis-SS1" src="https://github.com/user-attachments/assets/5e12109d-b232-459e-a733-f65625d95779" />

Dashboard View - Restaurants Type - Delivery Based

<img width="1636" height="911" alt="Zomato-restaurant-analysis-SS2" src="https://github.com/user-attachments/assets/5db1fc4d-798a-4a7d-a7db-6ed0abe12d15" />

Cleaned Dataset

<img width="1907" height="1084" alt="Zomato-restaurant-analysis-cleaned-dataset-SS" src="https://github.com/user-attachments/assets/f37cbaf1-51b6-4792-b583-b7d1551abc59" />

---

###  File Structure

```
Zomato-Restaurants-Analysis-Dashboard.pbix
│
├── Dashboard Page 1    → Main interactive dashboard with all visuals & slicers
└── Data Model          → Cleaned & transformed Zomato dataset (50,000+ rows, 17 columns)
```

---

###  Tools & Techniques Used

| Tool/Feature | Purpose |
|---|---|
| Power BI Desktop | Dashboard creation and data visualization |
| Power Query | Data cleaning, transformation & shaping |
| DAX Measures | Custom KPIs — Avg Rating, Total Votes, Avg Bill Amount |
| Slicers | Interactive filtering by cuisine, location, order type |
| Donut Chart | Restaurant type distribution visualization |
| Bar Chart | Top 10 restaurants ranking by performance |
| Gauge Chart | Avg bill amount range visualization |
| KPI Cards | Snapshot of key business metrics |
| Kaggle Dataset | Source — 50,000+ rows, 17 columns of Zomato data |

---

###  Key Insights & Business Decisions

- Analyzed **50,000+ restaurant records** across **17 attributes** including name, location, cuisine, rating, votes, bill amount, and service type
- Avg customer rating across all restaurants stands at **3.70 / 5.0**, indicating moderate satisfaction with significant room for quality improvement
- Total accumulated votes across all restaurants reached **25 Million**, reflecting high user engagement on the Zomato platform
- Avg bill amount of **₹604** per visit helps segment restaurants into budget, mid-range, and premium categories for targeted marketing
- **Casual Dining** dominates with **129 restaurants**, followed by Pub, Cafe (85) and Delivery-focused outlets (69), revealing strong dine-in culture
- Identified **Top 10 restaurants** (Onesta, Truffles, Empire Restaurant, Hammered, The Black Pearl, etc.) by vote count to highlight market leaders
- **Biryani + North Indian + Chinese** is the most popular cuisine combination, guiding menu recommendations for new entrants
- Restaurants offering **online ordering** show higher vote counts, suggesting digital presence directly impacts customer reach and revenue
- Location-based filtering across areas like **Banashankari, BTM, Brigade Road, Koramangala** enables hyperlocal business strategy planning

---

###  How to Use

- Download the `.pbix` file
- Open in **Power BI Desktop** (free download from Microsoft)
- Use the **Restaurant Type** buttons at the top to filter by category
- Use **Cuisines** slicer on the right to filter by food type
- Use **Location** slicer to drill down by area
- Toggle **Online Order** and **Book Table** slicers for service-type analysis
- Hover over charts for detailed tooltips

---

###  Dataset

- **Source:** [Kaggle — Zomato Restaurants Dataset](https://www.kaggle.com/)
- **Rows:** 50,000+
- **Columns:** 17
- **Key Fields:** Restaurant Name, Location, Cuisines, Rating, Votes, Avg Bill Amount, Online Order, Book Table, Restaurant Type

---

### 👤 Author

Anmol Tripathi
📧 anmoltripathi8329@gmail.com
