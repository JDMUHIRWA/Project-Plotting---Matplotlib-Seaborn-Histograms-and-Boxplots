**# Transport Fuel Efficiency Analysis using Matplotlib and Seaborn**

This project is part of the ASC23 coursework and focuses on analyzing vehicle data to understand transport-related patterns, particularly in fuel consumption, emissions, and correlations between vehicle features. The visualizations and interpretations aim to contribute to region-focused insights for climate action.

---

## 📂 Dataset

The dataset contains vehicle-related features such as:

* Make and Model
* Engine Size
* Fuel Type
* Fuel Consumption (City, Highway, Combined)
* CO2 Emissions
* Fuel Efficiency Score

Source: Provided via Google Drive for the assignment.

---

## ⚖️ Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 🎉 Visualizations

### 1. Histogram of Combined Fuel Consumption

* Shows the distribution of vehicles by their combined fuel usage (L/100km).
* Most vehicles fall between 20 and 30 L/100km, with a right-skew indicating fewer extremely high-consumption cars.

**Interpretation:** Majority of cars are moderately efficient, while few outliers consume significantly more fuel.

### 2. Heatmap of Correlation Matrix

* Displays correlations between all numeric features.
* Enabled with annotations (`annot=True`) for value clarity.

**Interpretation:**

* `UCity` and `city` are highly correlated; same for `UHighway` and `highway`.
* Suggests these columns may be redundant and candidates for dropping in modeling to reduce multicollinearity.
* Strong negative correlation found between fuel efficiency and CO2 emissions.

---

## 📚 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/your-repo-name.git
```

2. Open the notebook in Jupyter or Google Colab.
3. Run all cells from top to bottom.

---

## 📤 Files Included

* `analysis.ipynb` – Jupyter Notebook with plots and interpretations
* `plots/` – PNG images of histogram and heatmap
* `README.md` – This documentation file
* `fuel_ecomony_data.csv` - This is our data

---

## ✅ Rubric Checklist

* [x] Histogram plotted with correct numerical data
* [x] Histogram includes meaningful interpretation
* [x] Heatmap created with correlation values shown
* [x] Interpretation of which columns can be dropped included

---

## ✨ Author

* **Gustave Manzi & Jean Muhirwa Harerimana**
  Eastern College, ASC23 Coursework
  \[LinkedIn] | \[GitHub] | \[Email]

---

