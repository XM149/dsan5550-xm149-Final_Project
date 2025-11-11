## Project Structure and Carbon Emissions Tracking

All major model training and forecasting steps are implemented in the **main.ipynb**. This includes:

- **Daily and Monthly ARIMA models**
- **Daily and Monthly LSTM, XGBoost, and Random Forest models**

To monitor the environmental impact of model training, we integrated **CodeCarbon** into the main notebook. CodeCarbon tracks:

- CPU and RAM energy consumption
- Estimated CO₂ emissions during model training

We customized the tracker to save the emissions log in a data directory