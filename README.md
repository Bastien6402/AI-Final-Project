# AI in Aviation Engineering - Module C-250-01

**Project Title:** Aircraft Engine Predictive Maintenance (NASA C-MAPSS)
**Year:** 2024-2025
**Module Leader:** Dmitry Pavlyuk

---

## 👥 The Team
* **Student 1:** DESPONGE Bastien - st63806
* **Student 2:** COEYTAUX Mael - st63798


---

## ✈️ Project Overview
This project applies Artificial Intelligence techniques to address a critical challenge in aviation engineering: **Predictive Maintenance**.
Using the NASA C-MAPSS (Turbofan Engine Degradation Simulation) dataset, we developed a Machine Learning model capable of predicting the **RUL (Remaining Useful Life)** of an aircraft engine. The goal is to forecast engine failure before it occurs to optimize maintenance schedules and improve safety.

**Technical Objective:** Minimize the prediction error (RMSE) using regression algorithms.

---

## 📂 Project Portfolio (Table of Contents)

This repository serves as the public record of our group work.

| File / Item | Description | Contributors |
| :--- | :--- | :--- |
| **[Predictive_Maintenance_AI.ipynb](Predictive_Maintenance_AI.ipynb)** | The main Python notebook containing data loading, preprocessing, visualization, and the Random Forest model. | [Name 1] (60%), [Name 2] (40%) |
| **README.md** | Project documentation and overview. | [Name 1] (100%) |
| **Data Source** | NASA C-MAPSS Data (Loaded dynamically in the code). | NASA (External Source) |

---

## 📊 Methodology & Results

### 1. Data Preparation
We processed the raw sensor data to calculate the ground truth RUL for each engine. We visualized the degradation trends of key sensors (e.g., sensor s11) to confirm the correlation between sensor values and engine wear.

### 2. Modeling
We selected the **Random Forest Regressor** algorithm for its robustness and ability to handle non-linear relationships.
* **Training Set:** 80% of the fleet.
* **Test Set:** 20% of the fleet.

### 3. Performance
Our model achieved a Root Mean Squared Error (RMSE) of **41.4 cycles**.
The comparison plot (Prediction vs. Reality) demonstrates that the AI successfully tracks the degradation pattern of the engines.

---

## 🛠️ How to Run
1. Open the `.ipynb` file in Google Colab.
2. Upload the `train_FD001.txt` dataset (available from Kaggle or NASA repository).
3. Run all cells sequentially.

---

## 🔄 Process Evidence
* **Communication:** We used weekly meetings to coordinate tasks.
* **Tools:** Google Colab for development, GitHub for version control.
