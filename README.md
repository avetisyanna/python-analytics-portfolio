# Python Data Analytics Portfolio

## 📂 Project Structure
* **data/**: Contains raw and processed CSV files.
* **notebooks/**: Jupyter notebooks detailing the analysis process.
* **imgs/**: Visualizations and charts generated during analysis.

## 🛠️ Technologies Used
* Python3
* Pandas
* VS Code & Jupyter Notebooks

## 🚀 How to Run
1. Clone this repository.
2. Unzipping Archive.zip file:
```py
import zipfile
with zipfile.ZipFile("../data/raw/Archive.zip", "r") as zip_ref:
    zip_ref.extractall("../data/raw")
```
1. Activate the virtual environment: `source myenv/Scripts/activate`
2. Open the notebooks in the `notebooks/` folder.
