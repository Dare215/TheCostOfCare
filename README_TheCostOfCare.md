# The Cost of Care: Analyzing U.S. Drug Pricing for Brand vs. Generic Medications

**Author:** Darious Brown  
**GitHub:** [Dare215](https://github.com/Dare215)  
**Email:** dariousbrown3@icloud.com  

## 1) Project Overview
This project analyzes U.S. prescription drug costs, comparing brand-name and generic medications using Medicare Part D spending data. The goal is to identify the drugs that cost patients the most, reveal trends in pricing disparities, and provide data-driven recommendations for equitable and affordable healthcare.

## 2) Dataset
**Source:** CMS Medicare Part D Spending by Drug dataset  
- Covers 100% final-action Part D prescription claims.  
- Excludes over-the-counter medications.  
- Publicly available at: [CMS Data Portal](https://data.cms.gov)

## 3) Key Features
- **Cost Ranking:** Identify top-cost medications for patients and payers.
- **Brand vs. Generic Analysis:** Compare average spending, variability, and volume.
- **Savings Potential:** Calculate cost reductions from generic substitution.
- **Visual Analysis:** Use plots to highlight disparities.

## 4) Project Structure
```
TheCostOfCare/
│── Untitled48.ipynb                 # Jupyter Notebook with EDA & analysis
│── datasets/                         # Medicare drug cost data
│── reports/                          # PDF/DOCX written reports
│── README.md                         # Documentation
```

## 5) How to Run

### Option A — Python / Terminal
```bash
# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook "Untitled48.ipynb"
```

### Option B — PyCharm
1. Open the project folder in PyCharm  
2. Configure Python interpreter (point to `.venv`)  
3. Install dependencies from `requirements.txt`  
4. Run the notebook

## 6) Results Summary
- Brand-name drugs account for a disproportionate share of costs despite lower prescription volume.
- Generic alternatives offer 80–90% cost savings without compromising efficacy.
- Pricing disparities vary significantly by region and insurance plan.
- Encouraging generic substitution could reduce patient and system-wide costs.

## 7) Ethical Considerations
- Avoid inferring drug quality solely from price.
- Recognize bias toward insured patient data.
- Differentiate between “cost” (payer expense) and “price” (patient burden).
- Avoid stigmatizing high-cost life-saving treatments.

## 8) Future Enhancements
- Expand to multi-year datasets for trend analysis.
- Build a predictive pricing model.
- Integrate international drug price comparisons.

## 9) License
MIT License — Free to use with attribution.
