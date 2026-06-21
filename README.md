# Exploratory Data Analysis of Sampled Rental Listings from BuyRentKenya (Nairobi Metropolitan Area)

## Project Overview
This project presents an exploratory data analysis of 265 real rental listings manually collected from BuyRentKenya across 15 neighborhoods in the Nairobi Metropolitan Area. The analysis explores pricing patterns, property type distribution, furnishing premiums and amenity associations across the sampled listings.

This is not a comprehensive analysis of the entire Nairobi rental market — it is an exploration of a sample of listings available on BuyRentKenya at the time of data collection (June 2026).

---

## Objectives
- Understand the distribution of rental listings across neighborhoods and property types
- Explore how rent varies by number of bedrooms
- Examine whether furnished listings command higher rent than unfurnished ones
- Investigate whether amenities such as gym and swimming pool are associated with higher asking rent

---

## Data Source
- **Platform:** BuyRentKenya (www.buyrentkenya.com)
- **Collection method:** Manual data collection
- **Collection period:** June 2026
- **Total listings collected:** 265
- **Neighborhoods covered:** 15
- **Property types:** Apartment, House, Townhouse, Studio

---

## Dataset Description
| Column | Description |
|---|---|
| Neighbourhood | Area where the property is located |
| Property_ID | Unique identifier for each listing |
| Property_Type | Type of property (Apartment, House, Townhouse, Studio) |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| Rent (KSh) | Monthly asking rent in Kenyan Shillings |
| Furnished | Whether the property is furnished (Yes/No) |
| Parking | Whether parking is available (Yes/No) |
| Gym | Whether gym access is available (Yes/No) |
| Swimming Pool | Whether swimming pool is available (Yes/No) |
| Service Charge | Whether service charge applies (Yes/No) |
| Balcony | Whether the property has a balcony (Yes/No) |

---

## Tools Used
- **Microsoft Excel 2019** — data collection, cleaning, analysis and dashboard
- **PivotTables** — data summarization and analysis
- **PivotCharts** — data visualization
- **Excel Slicers** — interactive dashboard filtering

---

## Project Structure
```
Nairobi-Metropolitan-Rental-Listings-EDA/
│
├── Nairobi_Metropolitan_Rental_Listing_Analysis.xlsx
│   ├── Raw_Data        # Original collected data, unchanged
│   ├── Clean_Data      # Cleaned and standardized dataset
│   ├── Analysis        # PivotTables answering all business questions
│   ├── Dashboard       # Interactive visual dashboard
│   └── Insights        # Written EDA observations and findings
│
└── README.md
```
## Files Included
| File | Description |
|---|---|
| Nairobi_Metropolitan_Rental_Listing_Analysis.xlsx | Main Excel file containing all sheets — Raw Data, Clean Data, Analysis, Dashboard and Insights |
| EDA Dashboard.PNG | Screenshot of the interactive dashboard |
| README.md | Project documentation |

---

## Dashboard Preview
![EDA Dashboard](EDA%20Dashboard.PNG)

---

## Key Findings
1. **Apartments dominate the sample** — 194 out of 265 listings (73%) were apartments, making them the most commonly listed property type in the sample.

2. **Furnished listings show higher asking rent** — across all property types, furnished listings were priced higher than unfurnished ones. The gap was most notable in houses where furnished units averaged Ksh 704,500 compared to Ksh 332,085 for unfurnished.

3. **Gym access is associated with higher rent** — listings with gym facilities showed higher average asking rent across all property types. For apartments, gym listings averaged Ksh 144,786 compared to Ksh 101,971 without.

4. **Swimming pools are associated with higher asking rent** — properties with pools showed higher average rent across all property types. Among houses, pool listings averaged Ksh 474,500 compared to Ksh 312,104 without.

5. **Rent generally increases with bedroom count** — average asking rent rises consistently from Ksh 78,736 for 1-bedroom units to Ksh 418,805 for 5-bedroom properties. Notably, 6-bedroom properties averaged Ksh 368,000 — slightly lower than 5-bedroom — however this is based on only 4 listings and should be treated with caution.

6. **Some neighborhoods are underrepresented** — Ruaka (n=5), Kasarani (n=8), Hurlingham (n=8) and Ruiru (n=8) had very few listings. Observations for these areas should be interpreted with caution.

---

## How to Use
1. Download the file `Nairobi_Metropolitan_Rental_Listing_Analysis.xlsx`
2. Open in Microsoft Excel 2019 or later
3. Navigate to the **Dashboard** sheet for the interactive visual summary
4. Click on any item in the slicer to filter all charts. To reset, click the clear filter icon (≡✕) at the top right of each slicer
5. Visit the **Analysis** sheet to explore the underlying PivotTables
6. Visit the **Insights** sheet for written observations and findings
7. Raw and cleaned data are available in the **Raw_Data** and **Clean_Data** sheets respectively

---

## Excel Skills & Formulas Demonstrated
| Skill/Formula | Where Used |
|---|---|
| `SUMPRODUCT` | Counting unique neighborhoods in KPI summary |
| `INDEX/MATCH` | Identifying most common property type dynamically |
| `COUNTA` | Counting property types for KPI card |
| Data Validation | Dropdown lists applied to categorical columns in Clean_Data |
| PivotTables | 7 PivotTables built across all business questions |
| PivotCharts | 7 interactive charts connected to PivotTables |
| Slicers | 3 slicers filtering all charts simultaneously |
| Table Formatting | Clean_Data structured as an Excel Table |

---

## Limitations
- Data represents a sample of listings available on BuyRentKenya in June 2026 and may not reflect the full Nairobi rental market
- Affordable neighborhoods are significantly underrepresented on online listing platforms
- Listings may remain online after a property has been rented, meaning some listings may no longer be available
- Small sample sizes in certain neighborhoods limit the reliability of area-specific observations

---

## Author
**Valary Shikanda Etemesi**
Freelance Data Analyst | IT Support Specialist
📍 Nairobi, Kenya
🔗 [LinkedIn](https://www.linkedin.com/in/valary-shikanda-aa90162ba)
🐙 [GitHub](https://github.com/Valary-Shikanda)

---

*Data collected manually from BuyRentKenya, June 2026. This project was built entirely in Microsoft Excel 2019.*
