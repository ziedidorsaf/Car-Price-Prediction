# 🚗 Car Price Prediction

This project predicts the **selling price of cars** using **machine learning regression models**.
It leverages a dataset containing car specifications such as **brand, fuel type, body style, engine details, and safety ratings** to build predictive models.

The objective is to help buyers, sellers, and manufacturers estimate the **fair market value of cars** for better decision-making in the **automotive market**.

---

## 📊 Dataset

* **car_ID**: Unique identifier
* **symboling**: Insurance risk rating (+3 = risky, -3 = safe)
* **CarName**: Car brand/company name
* **fueltype**: Gas or Diesel
* **aspiration**: Aspiration method
* **doornumber**: Number of doors
* **carbody**: Body type (sedan, hatchback, etc.)
* **drivewheel**: Drive system type
* **enginelocation**: Engine placement
* … and more detailed technical specifications

---

## 📌 Key Steps in the Project

1. **Exploratory Data Analysis (EDA)**

   * Visualized relationships between features and price
   * Distribution checks and correlations

2. **Data Preprocessing**

   * Feature scaling with `StandardScaler`
   * Dimensionality reduction with **PCA**

3. **Modeling**

   * Linear Regression
   * Decision Tree Regressor
   * Random Forest Regressor
   * AdaBoost Regressor
   * Gradient Boosting Regressor

4. **Evaluation Metrics**

   * **Mean Squared Error (MSE)**
   * **Mean Absolute Error (MAE)**
   * **Root Mean Squared Error (RMSE)**
   * **R² Score**

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Scikit-learn** (regression, PCA, metrics)
* **SciPy**

---

## 📌 Results

* Models were trained and compared on predictive accuracy.
* Ensemble methods (**Random Forest, Gradient Boosting**) performed better than simple regression.
* Key predictors include **engine size, horsepower, curb weight, and car body type**.

---

## 🔑 Keywords

car price prediction, regression, machine learning, data science, car valuation, predictive modeling, random forest, gradient boosting

---

## 📌 Future Work

* Hyperparameter tuning for improved accuracy
* Deploy model as a web app with **Streamlit/Flask**
* Integrate real-world used-car datasets for better generalization

---

## 📜 License

This project is licensed under the MIT License.
