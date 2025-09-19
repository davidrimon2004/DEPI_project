# Sales Forecasting and Demand Prediction

## 📌 Overview
This project is the **graduation project of the Digital Egypt Pioneers Initiative (DEPI)** offered by **MCIT, Egypt**.  
It builds a machine learning model to predict **future sales and demand** using historical data and external factors (seasonality, promotions, holidays).  
The goal is to help businesses optimize **inventory, staffing, and marketing strategies**.

---

## 💻 Contributers
- David Rimon Youssef  **git hub account:** https://github.com/davidrimon2004
- Hanen Osama Fayez   **git hub account:** https://github.com/Hanenosama
- Youssef Mohamed Awad **git hub account** https://github.com/yosawad-3
- Mohamed Samy Gad Wasel **git hub account:** https://github.com/mohamed2005x
---

## 🎯 Objectives
- Collect and preprocess sales data  
- Explore sales patterns, seasonality, and external factors  
- Build and compare forecasting models (ARIMA, Prophet, Random Forest, LSTM)  
- Evaluate using MAE, RMSE, R²  
- Deploy the best model with MLOps for monitoring and retraining  

---

## 🛠️ Tech Stack
- **Languages**: Python  
- **Libraries**: Pandas, NumPy   
- **Version Control**: Git & GitHub  

---

# 📂 Data Instructions

The dataset used in this project is **stored on Google Drive** and not included directly in the repository to keep it lightweight.
**Google drive link:** https://drive.google.com/drive/folders/1I2UHoYxcy7lon1ZqyvUADWUjkrMQjXB4?usp=sharing

---

## 🔗 Accessing Data in Google Colab

1. **Mount Google Drive**:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
2. **Read data form the drive**
```python
import pandas as pd
data_path = "/content/drive/MyDrive/DEPI_project/data/your_dataset.csv"
df = pd.read_csv(data_path)
df.head()

---

## 📂 Structure
*(To be added later)*

---
