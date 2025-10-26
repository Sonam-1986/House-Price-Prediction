
## 🏠 **House Price Prediction Project**

### 📘 **Project Overview**

The **House Price Prediction** project is a **machine learning regression model** designed to predict **median house prices** using the **California Housing dataset** from Scikit-learn.
It preprocesses the data, builds pipelines for **Linear Regression** and **Random Forest Regressor**, evaluates model performance using various metrics, and provides an **interactive prediction interface** for user inputs.

This project demonstrates how **data preprocessing**, **model training**, **evaluation**, and **deployment-ready pipelines** work together in a practical ML workflow

### 🎯 **Objectives**

* To analyze housing data and understand relationships between features such as **income, house age, population, and location**.
* To build and compare multiple regression models for **predicting house prices**.
* To evaluate model accuracy using metrics like **MSE**, **RMSE**, **MAE**, and **R² Score**.
* To create a **user-interactive system** that allows users to input feature values and get real-time predictions.

### ⚙️ **Tools and Technologies Used**

* **Python 3** – Core programming language
* **Pandas & NumPy** – Data cleaning and numerical computation
* **Scikit-learn (sklearn)** – Model building, evaluation, and data handling
* **Joblib** – Saving and loading trained model pipelines
* **Argparse** – Command-line argument parsing for flexible usage
* **Google Colab / Jupyter Notebook** – Development and experimentation environment


### 🌟 **Key Features**

* 🧩 **Automatic Data Loading:** Fetches the **California Housing dataset** from Scikit-learn.
* ⚙️ **Preprocessing Pipeline:** Handles **missing values**, **feature scaling**, and **model integration** using Scikit-learn’s `Pipeline`.
* 🧠 **Multiple Regression Models:** Supports both **Linear Regression** and **Random Forest Regressor** for comparison.
* 📊 **Model Evaluation:** Displays key metrics such as **MSE**, **RMSE**, **MAE**, and **R² Score**.
* 💾 **Model Saving:** Exports trained models as `.joblib` files for reuse.
* 🗣️ **Interactive Prediction Mode:** Allows users to input custom feature values via command line and receive predicted house prices instantly.



### 💡 **Applications**

* 🏘️ **Real Estate Analytics:** Estimate property prices based on demographic and geographical data.
* 📈 **Data Science Education:** Demonstrates real-world regression workflows using Scikit-learn.
* 🔍 **Predictive Modelling:** Serves as a base for developing advanced AI models for housing markets.
* 🧮 **Research and Experimentation:** Useful for exploring feature importance, model tuning, and performance benchmarking.

### 🧰 **How to Run**

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction
   ```
2. Install dependencies:

   ```bash
   pip install numpy pandas scikit-learn joblib
   ```
3. Run the script:

   ```bash
   python house_price_prediction.py
   ```
4. For interactive mode:

   ```bash
   python house_price_prediction.py --interactive
   ```

### 🏁 **Conclusion**

This project showcases the power of machine learning in **predictive analytics**. By integrating **data preprocessing, regression algorithms, and model evaluation**, it delivers a practical solution for predicting house prices and serves as a strong foundation for further AI and data science applications.

