### Project Title  
**Smart Homes**  

### Case Study  
**Forecasting Energy Consumption for Improved Energy Efficiency in Smart Homes**  

---

## Description  
This project aims to predict energy consumption in smart homes by analyzing appliance activity, room occupancy, and external factors such as weather. The goal is to identify key factors influencing energy use and provide insights to optimize energy efficiency and reduce environmental impact.  

---

## Problem Statement  
Human activities are a major contributor to climate change, significantly impacting nature, other species, and future generations. To create a sustainable future, we need to adopt more mindful habits and work together. Improving energy efficiency in our homes is a crucial step in this direction.  

---

## Dataset  
The dataset used in this project was downloaded from Kaggle: [Smart Home Dataset with Weather Information](https://www.kaggle.com/datasets/taranvee/smart-home-dataset-with-weather-information).  
- **Data Volume:** Over 500,000 data points recorded at 1-minute intervals.  
- **Time Span:** Entire year of 2016.  
- **Predictors:** 32 variables including energy usage per room and appliance, outdoor weather conditions, and energy produced by the house itself.  

---

## Tools and Technologies Used  
This project was implemented in Python using the following libraries and tools:  
- **Matplotlib** and **Seaborn**: For data visualization.  
- **NumPy** and **Pandas**: For data manipulation and analysis.  
- **Scikit-learn**: For machine learning tasks, such as accuracy analysis and creating test/train datasets.  
- **TensorFlow**: For deep learning predictive modeling.  
- **Statsmodels**: For time series modeling.  

---

## Challenges  
- **Correlated Predictors:** Many of the 32 predictors exhibited inter-correlations.  
- **Data Quality Issues:** Missing values and mixed data types (e.g., string and numerical data in the same column).  
- **Complexity:** Column names required preprocessing for ease of use.  

To address these issues, the dataset was thoroughly preprocessed before modeling.  

---

## Results  
1. **Time Series Models:**  
   - Struggled to capture significant energy consumption spikes during summer months.  
   - Best prediction error: **24%**.  

2. **Feedforward Neural Networks:**  
   - Successfully identified energy consumption patterns.  
   - Achieved a prediction error as low as **13%**, demonstrating superior performance.  

---  
