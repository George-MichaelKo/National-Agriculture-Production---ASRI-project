# National Agriculture Production – ASRI Project

This project analyzes **U.S. agricultural productivity trends (1948–2019)** using data from the **Agricultural Sustainability and Research Initiative (ASRI)**. It explores the relationship between **Capital, Labor, and Intermediate Inputs** and their impact on **Total Output** and **Total Factor Productivity (TFP)**.

The repository includes:  
- **`national_ag_prod.csv`** – Dataset containing agricultural input/output data.  
- **`national_ag.py`** – Python script for data cleaning, analysis, and visualization.  
- **`ASRI 2025 Project Presentation.pdf`** – Project presentation summarizing insights and results.  

---

## 📊 Features
- **Correlation Analysis:** Identifies which inputs most influence Total Output and TFP.  
- **Growth Metrics:** Calculates Compound Annual Growth Rates (CAGR) for outputs and subcategories.  
- **Visualization:** Time-series charts to illustrate trends in productivity and input dynamics.  

---

## 🔍 Key Findings
- **Labor input declined steadily** from 1948 to 2019, while **capital and intermediate inputs increased**.  
- **Total Factor Productivity (TFP) showed strong long-term growth**, suggesting efficiency gains offset labor declines.  
- **Capital input had the strongest positive correlation** with both Total Output and TFP, followed by Intermediate Inputs.  
- **Purchased Services** (part of Intermediate Inputs) showed a **notable correlation** with TFP, implying they enhance efficiency through supporting farm operations.  
- **CAGR Analysis:**  
  - Total Output grew at **~1.4% per year**  
  - TFP grew at **~1.3% per year**, confirming technology-driven growth  

---

## 📈 Conclusion
Growth alone does not fully explain the **strong correlation between Purchased Services and both Total Output and TFP**.  
Their impact is likely due to:  
- **Consistent year-to-year use**  
- **Functional importance in core farm operations** (e.g., equipment maintenance, contract labor)  
- **Interactions with other inputs**, enhancing overall efficiency and productivity  

---

## 🔮 Next Steps
To build on this research, future work could explore:  
- **Regional or state-level trends** for more targeted insights  
- **Efficiency modeling** (e.g., TFP per dollar) for cost-benefit analysis  
- **Deeper input interaction analysis** to better understand cross-effects on productivity  

---

## ⚙️ Requirements
Ensure Python is installed along with the following libraries:  
```bash
pip install pandas matplotlib seaborn numpy
