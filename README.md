# 🚗 Impact of Car Features on Price and Profitability

## 📊 Project Overview

This data-driven project explores how various car features affect vehicle pricing and profitability for manufacturers. In the context of a rapidly evolving auto industry—marked by growing demand for fuel efficiency, hybrids, and sustainability—this project aims to provide actionable insights to guide strategic decisions in pricing, design, and market positioning.

**Key Question:**  
> How can a car manufacturer optimize pricing and product development to maximize profitability while meeting evolving consumer preferences?

---

## 🎯 Objectives

- Identify features most correlated with price and profit.
- Analyze trends in consumer preferences using popularity metrics.
- Compare performance vs. efficiency trade-offs (e.g., horsepower vs MPG).
- Provide pricing and product recommendations using regression modeling and segmentation.

---

## 🛠️ Tools & Techniques

- **Excel**: Data cleaning, pivot tables, dashboards  
- **EDA**: Trend analysis, correlation study  
- **Regression Modeling**: Feature importance, multivariate analysis  
- **Data Visualization**: Charts, bubble plots, combo charts  
- **Market Segmentation**: Category-based insights by fuel type, body style, and brand

---

## 📌 Key Findings

### 1. Car Model Popularity by Market Category
- **High Potential Segments**: *Crossover, Flex Fuel, Hybrid* combinations have extremely high popularity with low competition.
- **Overcrowded Segments**: *Luxury* and *Exotic* cars show low average popularity despite high model counts.

### 2. Engine Power vs Price (Regression)
- Strong positive correlation (`R² = 0.44`) between horsepower and MSRP.
- Engine HP adds ~$365 to the MSRP per unit HP on average.
- High-performance outliers suggest luxury/exotic pricing is not solely based on engine specs.

### 3. Feature Importance (Regression Analysis)
- **Most Influential Features**: Engine HP, Engine Cylinders
- **Moderate Impact**: Fuel efficiency (MPG)
- **Low Predictive Value**: Popularity (despite high marketing relevance)

### 4. Manufacturer Price Comparison
- **Luxury Leaders**: Bentley, Ferrari, Maybach dominate high average MSRPs.
- **Mid-Range**: Lexus, Acura, Pontiac cater to balanced segments.
- **Budget Brands**: Mitsubishi, GMC, Tesla (within this dataset) reflect cost-effective markets.

### 5. Cylinders vs Fuel Efficiency
- Clear negative correlation (`R² = 0.36`)—each added cylinder reduces MPG by ~3 units.

---

## 📊 Dashboards & Visual Analysis

### ✅ Car Price Distribution by Brand & Body Style
- Coupes dominate high-value segments; Sedans and SUVs rule the mainstream.
- Brands like Ferrari and McLaren focus almost entirely on Coupes and Convertibles.

### ✅ Fuel Efficiency Trend by Year & Body Style
- Significant MPG improvements post-2010, especially in hatchbacks and minivans.

### ✅ HP vs MPG vs Price (Bubble Chart)
- High HP = low MPG = high price (luxury cars)
- Efficient, budget-friendly cars cluster in the mid HP, high MPG region.

---

## 🧠 Business Impact

- **Pricing Strategy**: Use engine specs as baseline; add premium for design & innovation.
- **Product Development**: Focus on hybrid/flex-fuel performance cars.
- **Segmentation**: Target high-popularity, low-competition niches.
- **Sustainability**: Promote lower-cylinder models for eco-conscious consumers.

---

## 📁 Dataset

- Filename: `Dataset_Final.xlsx`
- Columns include: `Brand`, `Model`, `Engine HP`, `Cylinders`, `Fuel Type`, `Popularity`, `MSRP`, `Body Style`, `Transmission`, `City MPG`, `Highway MPG`, `Year`, and more.

---

## 📈 Future Work

- Expand to **multivariate regression** with interaction terms (e.g., `Engine HP × Fuel Type`).
- Integrate **real-time market price data** for dynamic pricing models.
- Build a **web dashboard** for interactive car feature analysis.

---

## 🙌 Acknowledgements

Thanks to open automotive datasets and inspiration from real-world pricing challenges in the automotive industry.
