# Demand Forecasting for Supply Chain Management Using Ensemble Deep Learning

This repository supports the research article titled **"Demand Forecasting for Supply Chain Management Using Ensemble Deep Learning"**, published in the **International Journal of Information Technology (Springer Nature)**. The journal is **indexed in Scopus**, and the article investigates and compares various machine learning and deep learning models for accurate demand forecasting in supply chain management.

📄 **DOI:** [https://doi.org/10.1007/s41870-024-02157-6](https://doi.org/10.1007/s41870-024-02157-6)

---

## 📘 Description

Supply chain management requires accurate demand forecasting to plan procurement, inventory, and delivery efficiently. This research focuses on evaluating and improving demand forecasting using a range of statistical and deep learning models, including:

- Classical models: **ARIMA**, **SARIMA**
- Deep learning models: **RNN**, **LSTM**, **GRU**, **BLSTM**
- Enhanced models: **LSTM with Ensemble Learning**

The paper explores ensemble learning in two variations:

1. **Without model pruning**: Averaging all LSTM models
2. **With model pruning**: Removing underperformers and averaging the top models

---

## 📊 Results

Experiments were conducted using a public dataset from the **University of Chicago**. Notably, the **LSTM model enhanced through ensemble learning with model pruning** achieved a **very low RMSE of 9.26**, demonstrating the potential of this method in improving prediction accuracy for customer demand.

---

## 📂 Dataset

The dataset used in this study is publicly available and can be accessed here:

🔗 [Dominick's Finer Foods Dataset - University of Chicago](https://www.chicagobooth.edu/research/kilts/research-data/-/media/enterprise/centers/kilts/datasets/dominicks-dataset/movement_csv-files/wptw.zip)

---

## 🧠 Key Contributions

- Comparative analysis of traditional and deep learning models
- Implementation of ensemble learning to enhance LSTM forecasts
- Introduction of model pruning to boost ensemble efficiency
- Practical implications for supply chain forecasting and planning

---

## 📌 Citation

If you use or reference this work, please cite the original paper:

> Zishan Ahmad, et al. (2024). Demand Forecasting for Supply Chain Management Using Ensemble Deep Learning. *Innovations in Systems and Software Engineering.*  
> [https://doi.org/10.1007/s41870-024-02157-6](https://doi.org/10.1007/s41870-024-02157-6)

---