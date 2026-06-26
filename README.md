# Effects of Historic Redlining on Transit Access and Employment in Detroit

## 🎯 Project Overview

This project examines how 20th-century redlining and racially discriminatory urban policy continues to shape economic opportunity and transit access in Detroit. Using GIS spatial analysis, statistical regression modeling, and data visualization, we demonstrate that car ownership is strongly correlated with both access to employment in high-demand industries and higher median income, while reliance on transit is tied to economic disadvantage.

**Key Finding:** Detroit remains the largest U.S. metro area without a functional regional transit system, leaving residents in the urban core—now over 80% Black—cut off from jobs that have shifted to suburban areas.

---

## 📊 Methodology

### Data Sources
- HOLC Redlining historical data (1930s)
- U.S. Census Bureau American Community Survey
- Detroit employment location data (Ford, GM, FCA)
- Public transit network data (DDOT, SMART)
- EPA Accessibility Index

### Techniques Used
- **Spatial Analysis:** ArcGIS Pro network analysis, travel-time isochrones
- **Statistical Modeling:** OLS regression quantifying relationships between transit access, car ownership, and employment outcomes
- **Data Visualization:** Choropleth maps, 3D scatter plots, employment accessibility comparisons
- **GIS Mapping:** HOLC redlining indicators, racial demographics, job site distribution

### Tools & Languages
- **ArcGIS Pro** — spatial analysis and network modeling
- **Python** — data processing (pandas), statistical modeling (statsmodels), visualization (matplotlib, seaborn)
- **Jupyter Notebook** — interactive analysis and documentation

---

## 🔍 Key Findings

1. **Spatial Mismatch Confirmed:** Car owners can access 2-4x more jobs than transit-dependent residents within 30-minute commutes

2. **Income Correlation:** Every 1% increase in car ownership correlates with **$574.34 increase** in median income

3. **Transit Disadvantage:** Every 1% increase in bus ridership correlates with **$20.26 decrease** in median income

4. **Historic Segregation Persists:** Detroit's urban core received the most severe redlining designations in the 1930s and remains 80%+ Black today, while surrounding suburbs are predominantly white

5. **Employment Concentration:** Major auto industry employers (Ford, GM, FCA) are concentrated in suburban areas with limited transit coverage

6. **Regional Transit Failure:** Michigan Public Act 55 (1963) allowed 50+ suburban municipalities to opt out of funding Detroit's transit system, fragmenting regional mobility

---

## 📁 Repository Structure
---detroit-transit-equity-analysis/

├── Motown_Mo__Buses.ipynb              # Main analysis notebook with all code and visualizations

├── Final_Project.pdf                   # Complete written report with findings

├── 3130_Project_supplement.pdf         # Supplementary analysis and visualizations

└── README.md                           # This file

## 🛠️ How to Use This Project

### View the Analysis
1. Open `Motown_Mo__Buses.ipynb` in Jupyter Notebook or Google Colab
2. Run cells sequentially to reproduce all maps and regression models
3. Refer to PDFs for full written analysis and interpretations

### Key Visualizations Included
- HOLC Redlining Indicator Map (1930s) showing historical discrimination
- Current Black Population Distribution across Detroit neighborhoods
- Spatial Mismatch mapping (Job access vs. car ownership disparities)
- EPA Job Accessibility Index comparisons (Car vs. Transit access)
- Travel-Time Isochrones showing realistic commute times
- 3D Regression Analysis visualizing employment and income correlations
- Auto Industry Job Distribution maps and statistics

---

## 💡 Key Insights for Planning & Policy

**Short-term Strategy:** Increasing car access for low-income residents may be the most effective immediate solution

**Medium-term Strategy:** Affordable housing should be prioritized near high-frequency transit corridors

**Long-term Strategy:** Regional transit integration across DDOT/SMART boundary is critical for equity

**Policy Implication:** Current transit investment favors already-affluent areas; funding rebalancing is needed

---

## 🎓 Skills Demonstrated

✅ GIS Spatial Analysis (ArcGIS Pro)  
✅ Statistical Regression Modeling (OLS, interpretation)  
✅ Python Data Analysis (pandas, statsmodels, matplotlib, seaborn)  
✅ Cartography & Map Design  
✅ Urban Planning & Spatial Mismatch Theory  
✅ Quantitative Research Methods  
✅ Data Visualization & Storytelling  
✅ Historical Context Analysis (Redlining, segregation)  

---

## 📚 Theoretical Framework

This project builds on **The Spatial Mismatch Hypothesis** (Kain, 1968), which argues that Black workers in inner cities experience disproportionately low employment due to:
1. Housing discrimination
2. Decentralization of jobs to suburban areas
3. Inadequate transit options

Our analysis demonstrates that this theory remains highly relevant in contemporary Detroit, with measurable quantitative evidence.

---

## 📖 References

- McBride, S. (2020). The Big Divide: Detroit's Transportation Crisis. Detroit Free Press.
- University of Michigan Detroit Metro Area Communities Study (DMACS). (2025). Transportation Insecurity in the Motor City.
- Kain, J.F. (1992). The Spatial Mismatch Hypothesis: Three Decades Later. Housing Policy Debate.
- Regional Transit Authority of Southeast Michigan. (2022). Detroit Workforce Mobility Equity Analysis: Gap Analysis Report.
- Gallagher, R., et al. (Eds.). (2015). Mapping Detroit: Land, Community, and Shaping a City. Wayne State University Press.

---

## 📧 About This Project

**Author:** Abduljellil Haj Hamid  
**Institution:** Cornell University | B.S. Urban & Regional Planning (May 2026)  
**Minors:** Real Estate, Inequality Studies  
**Course:** INFO 3130 (Data and the State)  
**Term:** Spring 2025  

**Contact:** ahh87@cornell.edu  
**LinkedIn:** linkedin.com/in/abduljellil-hamid-918bb2242  

---

## 🔗 Skills for Real Estate & Planning Roles

This project demonstrates expertise relevant to:
- **Real Estate Development & Analysis** — GIS site selection, market accessibility
- **Urban Planning & Policy** — spatial analysis, equity-focused planning
- **ESG & Impact Investing** — analyzing social determinants of opportunity
- **Transportation Planning** — network analysis, accessibility modeling
- **Data-Driven Decision Making** — regression analysis, quantitative research
