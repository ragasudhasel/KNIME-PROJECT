# ⚡ Smart Energy Consumption Prediction – KNIME Workflow

This project uses the **KNIME Analytics Platform** to build a visual, no-code pipeline that analyzes historical energy usage data and predicts future consumption patterns. It aims to help industries, households, and planners optimize energy usage efficiently.

---

## 🎯 Project Goals

- Understand energy consumption trends over time
- Clean and preprocess raw energy data
- Use regression models to forecast future energy use
- Visualize results with interactive charts and outputs

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|---------|
| **KNIME** | Workflow design & ML |
| **CSV Dataset** | Input data |
| **Regression Nodes** | Prediction modeling |
| **Plot Nodes** | Data visualization |
| **Scorer / Statistics Nodes** | Performance evaluation |

---

## 📊 Key Workflow Components

- **Data Reader** – Load raw CSV data
- **Missing Value** – Handle null or missing values
- **Normalizer** – Standardize input values
- **Linear & Decision Tree Regression** – Model energy prediction
- **Line Plot / Bar Plot** – Visualize trends and predictions
- **Scorer** – Evaluate model accuracy (e.g., RMSE)

---

## 🗂️ Project Contents

```bash
energy-prediction-knime/
├── energy_forecast.knwf          # Main KNIME workflow
├── energy_data.csv               # Dataset file
├── screenshots/
│   ├── full_workflow.png
│   ├── prediction_output.png
└── README.md
