# Fisheries Stock Assessment Using Catch and Oceanographic Data

This project demonstrates a basic stock assessment model using synthetic fisheries catch data combined with environmental/oceanographic variables such as **temperature**, **salinity**, and **chlorophyll concentration**. It is intended for researchers, data scientists, and students interested in fishery science and data modeling.

---

## 📊 Objective

To estimate fish catch using a regression-based stock assessment model and visualize the relationship between oceanographic conditions and fisheries data.

---

## 📁 Project Structure

fisheries-stock-assessment/
├── data/
│ └── synthetic_fisheries_data_with_predictions.xlsx
├── src/
│ └── stock_assessment.py
├── notebooks/
│ └── analysis.ipynb (optional)
├── environment.yml
└── README.md

yaml
Copy
Edit

---

## 🧪 Features

- Generates **synthetic data** mimicking real-world fisheries and environmental parameters.
- Trains a **linear regression model** to predict fish catch.
- Outputs an Excel file with predictions.
- Visualizes **Observed vs Predicted Catch**.

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/fisheries-stock-assessment.git
cd fisheries-stock-assessment
2. Create Conda Environment
bash
Copy
Edit
conda env create -f environment.yml
conda activate fisheries-stock-env
3. Run the Main Script
bash
Copy
Edit
python src/stock_assessment.py
This will generate:

A synthetic dataset

Predicted catch values

A visualization comparing observed vs predicted catch

📁 Data Output
synthetic_data.csv – Raw synthetic data.

synthetic_fisheries_data_with_predictions.xlsx – Includes predicted catch from the regression model.

📈 Example Visualization
The project produces a scatter plot of actual vs predicted catch with an ideal fit line to visually assess model performance.

📚 Requirements
Python 3.10+

pandas

numpy

matplotlib

seaborn

scikit-learn

jupyter (optional)

✍️ Author
Agbozu Ebingiye Nelvin
Environmental Data Scientist
GitHub: @Nelvinebi

