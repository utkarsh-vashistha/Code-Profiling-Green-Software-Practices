# Code-Profiling-Green-Software-Practices

# **Crop Yield Prediction Using Machine Learning**  

## **Project Overview**  
This project focuses on predicting **crop yield (tons per hectare)** using machine learning models based on **environmental, soil, and vegetation parameters**. The goal is to help **farmers, agronomists, and researchers** make data-driven decisions to optimize crop production.  

## **Machine Learning Models Used**  
The project includes two models for comparison:  

### **Random Forest Regressor**  
- A **tree-based ensemble learning algorithm**.  
- Reduces **overfitting** and captures **complex relationships** between variables.  
- Works well with **non-linear data** and large datasets.  

### **Gradient Boosting Regressor**  
- A **boosting-based model** that sequentially corrects previous prediction errors.  
- Highly accurate for **structured data**.  
- Often outperforms other models in **agricultural forecasting**.  


# **Energy Consumption Analysis Using CodeCarbon**  

## **Why Use CodeCarbon?**  
Machine learning models consume significant **computational resources**, leading to **energy consumption** and **carbon emissions**. CodeCarbon helps:  
✅ Track and **measure** the energy consumed during model training.  
✅ Estimate **carbon footprint** based on hardware and power usage.  
✅ Provide insights to **optimize ML models** for efficiency.  

## **Tracked Energy Metrics**  
The following parameters are recorded to analyze energy efficiency:  

| **Metric**         | **Description** |
|-------------------|----------------|
| `timestamp`       | The time when energy measurement was recorded. |
| `duration`        | The total execution time of the ML training process. |
| `emissions`       | The **total CO₂ emissions (kgCO₂e)** generated. |
| `emissions_rate`  | The rate of emissions per second (kgCO₂e/sec). |
| `cpu_power`       | The power consumed by the **CPU** (Watt). |
| `cpu_energy`      | The **energy usage of CPU** during training (kWh). |
| `ram_energy`      | The **energy used by RAM** (kWh). |
| `energy_consumed` | The **total energy** consumed by the system (kWh). |

## **Comparison Between Models**  
By tracking these metrics, we can compare:  
- **Random Forest vs. Gradient Boosting** in terms of energy consumption.  
- The **trade-off** between **model accuracy** and **carbon footprint**.  
- How **hyperparameter tuning** affects power usage.  

## **Key Findings & Optimization**  
- **If one model consumes less energy** while maintaining high accuracy, it’s preferable for sustainable AI.  
- **Reducing dataset size** and **early stopping** can minimize emissions.  
- Optimizing **CPU vs. GPU usage** can impact energy efficiency.  

By integrating **CodeCarbon**, this project aims to make **crop yield prediction** not only accurate but also **energy-efficient**!
