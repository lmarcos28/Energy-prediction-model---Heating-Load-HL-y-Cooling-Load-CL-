# 🏢⚡ Energy Prediction Model – Heating Load (HL) & Cooling Load (CL)

This project was built using the [Energy Efficiency Dataset](https://archive.ics.uci.edu/dataset/242/energy+efficiency) from the UCI Machine Learning Repository.  
It focuses on predicting the **heating load (HL)** and **cooling load (CL)** of buildings using **Machine Learning models**.  

The dataset contains samples from different building shapes and configurations, with **8 input features** describing physical and design properties of each building.  
The goal is to predict the **energy demand** required for heating and cooling.  

---

## 📊 Dataset Description

Each row in the dataset corresponds to a different building design, and the features/targets are defined as follows:

### 🔹 Features (Inputs to the model)
- **X1 = Relative Compactness** → A dimensionless measure of how compact a building is compared to a reference building with the same volume. Higher values = more compact and usually more energy efficient.  
- **X2 = Surface Area**  
- **X3 = Wall Area**  
- **X4 = Roof Area**  
- **X5 = Overall Height**  
- **X6 = Orientation** (1–4, categorical)  
- **X7 = Glazing Area** (ratio of glass to total façade area)  
- **X8 = Glazing Area Distribution** (0–5, categorical distribution of glazing across building sides)  

### 🔹 Targets (Outputs predicted by the model)
- **Y1 = Heating Load (HL)** → Energy demand required for heating.  
- **Y2 = Cooling Load (CL)** → Energy demand required for cooling.  

---

## 🚀 Technologies Used
- [Python 3](https://www.python.org/)  
- [pandas](https://pandas.pydata.org/) → Data manipulation  
- [matplotlib](https://matplotlib.org/) & [seaborn](https://seaborn.pydata.org/) → Data visualization  
- [scikit-learn](https://scikit-learn.org/) → Machine Learning models (Random Forest, Linear Regression, etc.)  
- [openpyxl](https://openpyxl.readthedocs.io/) → Reading Excel data  

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Energy-prediction-model.git
   cd Energy-prediction-model


