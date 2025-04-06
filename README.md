# 💻 Laptop Price Prediction using Machine Learning
<img src="https://github.com/goldstring/laptop_price_prediction_using_machine_learning_regression/blob/main/3519517_791.jpg?raw=true" />

## 🏢 Industry Domain
**E-commerce / Retail / Electronics**

This project falls under the **retail and e-commerce** domain, where predicting laptop prices based on configuration and features helps businesses in pricing strategy, inventory planning, and customer recommendations.

---

## 🧩 Problem Statement

In the modern digital world, laptops come with a wide variety of configurations and prices. Customers often get confused about whether the price they are paying is fair or not. Retailers and resellers also need accurate price predictions for inventory decisions and resale value estimation.

**Objective**:  
To build a machine learning model that can predict the price of a laptop based on its specifications such as processor, RAM, storage type, screen size, etc.

---

## 📦 Dataset Description

The dataset contains information about various laptops and their technical specifications along with the selling price.

**Source**: Publicly available dataset scraped from online retailers like Flipkart or Amazon.

### 🔑 Key Columns (Features):

| Feature Name      | Description                                     |
|-------------------|-------------------------------------------------|
| Company           | Brand of the laptop                             |
| TypeName          | Type of laptop (Ultrabook, Gaming, etc.)        |
| Inches            | Screen size in inches                           |
| ScreenResolution  | Screen resolution and quality                   |
| Cpu               | Processor details (brand, speed, etc.)          |
| Ram               | RAM size in GB                                  |
| Memory            | Storage type and capacity (HDD/SSD)             |
| Gpu               | Graphics processing unit                        |
| OpSys             | Operating system installed                      |
| Weight            | Weight of the laptop                            |
| Price             | Selling price of the laptop (target variable)   |

---

## 🧠 Approach

1. **Data Preprocessing**:  
   - Handled categorical encoding  
   - Converted screen resolution and storage into usable numeric values  
   - Extracted brand-level details from CPU and GPU strings  

2. **Exploratory Data Analysis (EDA)**:  
   - Analyzed price distribution across companies and configurations  
   - Visualized trends using plots for better understanding  

3. **Model Building**:  
   - Applied multiple regression models: Linear Regression, Ridge, Lasso, Random Forest  
   - Used GridSearchCV for hyperparameter tuning  

4. **Evaluation**:  
   - Metrics used: R² Score, MAE, RMSE  

---

## ✅ Conclusion

- The model accurately predicts the price of a laptop with a high R² score on test data.
- Important features influencing laptop prices: **CPU brand**, **RAM**, **SSD size**, **GPU**, and **Screen Resolution**.
- This model can be used in e-commerce platforms for **automated pricing engines**, or in consumer tools for **price fairness checks**.

---

## 🚀 Future Work

- Include latest laptops and prices for real-time predictions  
- Deploy the model using Flask/Streamlit for interactive web applications  
- Integrate user review scores and battery backup as additional features

---

## 📌 Tools & Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
