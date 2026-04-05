# 📈 Python Data Analytics Portfolio

This repository documents my progression from Python fundamentals to advanced business analytics. The project is structured as a technical roadmap, evolving from data cleaning to interactive storytelling and customer behavioral analysis.

## 📁 Project Structure

* **data/**: Raw and processed datasets (Instacart, Customer records).
* **notebooks/**: Detailed analysis and step-by-step technical implementation.
* **imgs/**: Exported visualizations and data insights.
* **templates.py**: Custom utility module for reusable, production-ready plotting functions.

## 🛠️ Technologies Used

* **Python 3**: Core logic and automation.
* **Pandas & NumPy**: High-performance data manipulation and aggregation.
* **Plotly Express**: Dynamic, interactive data visualizations.
* **RFM Framework**: Marketing analytics for customer segmentation.

## 🗺️ Learning Roadmap & Skills Acquired

### 🏗️ Phase 1: Foundations of Data Programming
Mastered Python syntax, data structures, and the logic required to handle complex datasets efficiently.

### 🧹 Phase 2: Data Manipulation & Wrangling
Advanced proficiency in **Pandas**, focusing on cleaning "dirty" data, merging disparate datasets, and performing complex group-by aggregations to extract meaningful summaries.

### 📊 Phase 3: Exploratory Data Analysis (EDA) & Visualization
Developed a deep understanding of visual storytelling. This includes:
* **Static Analysis**: Using core principles to design clear, insightful charts.
* **Interactive Dashboards**: Leveraging **Plotly** to create zoomable, hoverable, and filterable visualizations.
* **Time-Series Analysis**: Handling date-time objects to uncover trends over weeks, months, and years.

### 🎯 Phase 4: Business Intelligence & Segmentation
Applied analytical models to real-world scenarios, specifically implementing **RFM (Recency, Frequency, Monetary)** analysis to segment customers and identify high-value cohorts.

---

## 🚀 How to Run

1. **Clone this repository**:
   ```bash
   git clone <your-repo-link>
   ```
2. Unzipping Archive.zip file:
```py
import zipfile
with zipfile.ZipFile("../data/raw/Archive.zip", "r") as zip_ref:
    zip_ref.extractall("../data/raw")
```
3. Activate the virtual environment: `source myenv/Scripts/activate`
4. Open the notebooks in the `notebooks/` folder.
