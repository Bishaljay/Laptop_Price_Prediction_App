# 💻 Laptop Price Prediction App

A Machine Learning-based web application that predicts the price of a laptop based on its specifications like brand, processor, RAM, storage, GPU, operating system, and more.

## 🚀 Demo

[Insert link here if deployed – e.g., Streamlit, Heroku, or Render]

## 📌 Features

- Predict laptop prices using machine learning models
- User-friendly web interface
- Input fields for brand, processor, RAM, storage, screen size, and more
- Real-time price prediction
- Powered by Streamlit
- Trained on cleaned and preprocessed laptop dataset

## 🛠️ Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Python  
- **ML Model**: Random Forest (or specify the model you used)  
- **Libraries**: pandas, numpy, scikit-learn, joblib, streamlit

## 📂 Project Structure

```

Laptop_Price_Prediction_App/
│
├── app.py                # Main application script
├── model.pkl             # Trained ML model
├── laptop\_data.csv       # Dataset used for training
├── requirements.txt      # Required Python packages
├── README.md             # Project documentation
└── images/               # Optional screenshots or icons

````

## 📊 Dataset

- The dataset contains specifications of various laptops and their respective prices.
- Features include: Brand, Processor, RAM, Storage, GPU, Operating System, etc.
- Dataset source: [Github](https://github.com/Bishaljay/Laptop_Price_Prediction_App/blob/main/Dataset/laptop_price.csv)

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/Laptop-Price-Prediction-App.git
cd Laptop-Price-Prediction-App
pip install -r requirements.txt
````

## 🧠 How It Works

1. User enters laptop specifications into the form.
2. The input is transformed and fed into a trained ML model.
3. The model outputs the predicted price of the laptop.
4. The result is displayed on the interface.

## ▶️ Run the App

Using **Streamlit**:

```bash
streamlit run app.py
```
