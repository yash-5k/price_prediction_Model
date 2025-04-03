
# Bus Price Prediction Model

## 📌 Project Overview
This project aims to develop a machine learning model for predicting bus ticket prices based on various factors such as distance, time of travel, type of bus, and other relevant parameters. The goal is to help commuters and travel companies estimate ticket prices efficiently.

## 📊 Dataset
The dataset includes the following features:
- **Source & Destination**: Journey start and end locations
- **Date & Time of Journey**: Travel schedule
- **Bus Type**: AC, Non-AC, Sleeper, etc.
- **Seat Availability**: Available seats count
- **Travel Distance**: Total distance covered
- **Fare for Child & Adult**: Target variables representing ticket prices

## 🏗️ Model Development
### Steps:
1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
2. **Exploratory Data Analysis (EDA)**:
   - Understanding distributions and correlations
3. **Model Training**:
   - Tested models: Linear Regression, Random Forest, XGBoost, Neural Networks
   - Hyperparameter tuning for better accuracy

## 🎯 Performance Evaluation
The model performance was assessed using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared Score**

## 🚀 Installation & Usage
### Prerequisites
- Python 3.x
- Required Libraries:
  ```sh
  pip install pandas numpy scikit-learn matplotlib seaborn xgboost
  ```

### Running the Model
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/bus-price-prediction.git
   ```
2. Navigate to the project folder:
   ```sh
   cd bus-price-prediction
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
   Open `bus_price_prediction.ipynb` and execute the cells.

## 🔮 Future Enhancements
- Real-time data integration for dynamic pricing
- Additional factors like weather & traffic impact
- Web application for easy access



