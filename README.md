# Venezuela Upstream Asset Inventory & Valuation

## Project Overview
This project delivers a structured, data-driven analysis of Venezuela’s upstream oil and gas assets, with particular emphasis on the transition from legacy producing basins (Maracaibo and Oriente) to the extra-heavy crude developments of the Orinoco Belt.

The objective is to enable stakeholders to:
- Compare operational efficiency across legacy and emerging assets  
- Identify production bottlenecks driven by infrastructure decay  
- Assess asset longevity using Reserve-to-Production (R/P) ratios  
- Understand portfolio risk related to oil grade, geography, and development status  

This analysis is designed to reflect real-world upstream portfolio evaluation practices used in energy economics and asset management.

---

## Key Features
- **Data Engineering & Cleaning**  
  - Normalization of non-standard reserve estimates  
  - Conversion of reserve ranges into statistically representative mean values  

- **Asset Lifecycle Analysis**  
  - Classification of fields by operational status: Active, Development, Mature, Declining  

- **Portfolio Distribution Analysis**  
  - Visualization of production capacity by basin and oil grade  

- **Strategic Metrics**  
  - Reserve-to-Production (R/P) ratio calculations  
  - Identification of long-life “Growth Giants” versus short-cycle “Cash Cows”  

- **Risk Assessment**  
  - Extraction of qualitative operational risks from unstructured engineering notes using string parsing techniques  

---
## Tech Stack

* **Language:** Python
* **Core Libraries:**

  * `pandas` – data manipulation and transformation
  * `numpy` – numerical and statistical logic
  * `plotly` – interactive visualizations
  * `matplotlib` / `seaborn` – static statistical charts

---

## Sample Insights

* **Concentration Risk:** More than 70% of total production capacity is concentrated in the Orinoco Belt, increasing exposure to development and infrastructure risk.
* **Development Dependency:** The five highest-capacity fields are primarily in the Development phase, indicating reliance on future capital execution rather than existing production.
* **Crude Quality Exposure:** Extra-heavy crude dominates the portfolio, requiring significant upgrading, dilution, and logistics infrastructure to remain economically viable.

---

## Setup & Installation

1. Clone the repository:

```bash
git clone https://github.com/jeffreydarlington/venezuela-upstream-analysis.git
```

2. Install dependencies:

```bash
pip install pandas numpy plotly matplotlib seaborn
```

3. Run the analysis scripts:

```bash
python src/data_processor.py
python src/visualization.py
```

---

## Author

**Jeffrey Darlington**
Junior Data Analyst / Software Engineer

LinkedIn: [http://linkedin.com/in/jeffrey-darlington/](https://www.linkedin.com/in/your-link-here)

---

## Notes

This project is intended for educational and portfolio demonstration purposes.
Data sources and assumptions are documented within the notebooks for transparency and reproducibility.
Data Source: [https://www.kaggle.com/datasets/umarnabibhat/oil-reservoirs-dataset-of-venezuela/data]
```
