# 🏠 House Price Prediction

## 📌 Project Overview
This project predicts house prices using Machine Learning models like Linear Regression, Random Forest, and XGBoost. It uses the **Ames Housing Dataset** and is deployed via a Flask API.

## 📁 Project Structure

House-Price-Prediction/ │── data/ # Dataset (if applicable) │── models/ # Saved model files │── app.py # Flask API for predictions │── house_price_prediction.ipynb # Jupyter Notebook with ML code │── requirements.txt # Dependencies │── README.md # Project Documentation │── .gitignore # Ignored files for Git

Install dependencies:
pip install -r requirements.txt

Run Jupyter Notebook for data analysis:
jupyter notebook

Run the Flask API (for deployment):
python app.py

API Usage
Request Body (JSON Example):
{
   "feature1": value,
   "feature2": value,
   ...
}

Response:
{
   "prediction": [house_price]
}

 License
This project is licensed under the MIT License.

🤝 Contributing
Feel free to submit a pull request! 😊
