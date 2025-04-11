# 💻 Laptop Price Prediction App

This is a Streamlit-based web application that predicts the price of a laptop based on various features like brand, processor, RAM, storage, and more. The app uses a trained machine learning pipeline to make predictions.

## 🚀 Features

- Interactive UI built with Streamlit
- Input form to enter laptop specifications
- Predicts approximate laptop price
- Pre-trained ML pipeline for fast inference

## 📁 Project Structure

```
Laptop_Price_Prediction_App/
├── app.py                  # Streamlit app main file
├── pipe.pkl                # Trained machine learning pipeline
├── requirements.txt        # List of required packages
└── README.md               # Project documentation
```

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Laptop_Price_Prediction_App.git
   cd Laptop_Price_Prediction_App
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate     # For Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

## 📦 Dependencies

Your `requirements.txt` should include packages like:

```
streamlit
pandas
numpy
scikit-learn
xgboost
lightgbm
```

## 🧑‍💻 Author

Bishal Jaysawal

