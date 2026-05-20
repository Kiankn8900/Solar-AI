# ☀️ Solar AI — Intelligent Solar Panel Angle Prediction System

## Overview

Solar AI is an AI-powered system designed to predict the optimal tilt angle for solar panels using environmental and atmospheric data.

This project combines:

* Deep Learning
* LSTM Neural Networks
* Time-Series Analysis
* Professional User Interface
* Environmental Data Processing
* Real-Time Prediction System

The main goal of the project is to improve solar energy efficiency by intelligently adjusting solar panel angles under different weather conditions.

---

# 🚀 Features

## 🧠 AI Prediction Engine

* Multi-layer LSTM model
* Time-series forecasting
* Built with PyTorch
* GPU & CUDA support

## 📊 Advanced Feature Engineering

The model uses:

* Temperature
* Relative Humidity
* Wind Speed
* Cloud Type
* Aerosol Optical Depth
* Atmospheric Water Vapor
* DNI
* DHI
* Cyclic Hour Encoding
* Seasonal Cyclic Encoding

## 🎨 Professional User Interface

* Fully customized Streamlit UI
* Dynamic Dark & Light Mode
* Custom animations
* AI loading system
* Custom SVG icons
* Responsive design

## ⚡ Performance Optimization

* Cached model loading
* Cached scaler loading
* Fast preprocessing pipeline
* Optimized real-time inference

---

# 🏗️ Project Structure

```text id="u5l2pq"
Solar AI
│
├── app.py                                                        # Main Streamlit application
├── model.py                                                      # LSTM model architecture
├── utils.py                                                      # Data preprocessing utilities
├── style.css                                                     # Full custom UI styling
│
├── solar_lstm.pth                                                # Final trained AI model
├── best_model.pth                                                # Best saved checkpoint
├── scaler_X.pkl                                                  # Feature scaler
├── scaler_y.pkl                                                  # Target scaler
├── config.pkl                                                    # Model configuration and features
│
├── Intelligent_system_for_predicting_the_optimal_angel_of_solar_panels_v5.f.ipynb
│                                                                 # Main notebook for AI training and development
│
├── assets/
│   └── logo.png                                                  # Project logo
│
├── data/
│   ├── 2017.csv                                                  # 2017 dataset
│   ├── 2018.csv                                                  # 2018 dataset
│   └── 2019.csv                                                  # 2019 dataset
│
└── README.md
```

---

# 🧠 AI Model Details

## Model Type

LSTM (Long Short-Term Memory)

## Model Architecture

* Features: 12
* Hidden Size: 64
* Number of Layers: 3
* Dropout: 0.2
* Output: Optimal Solar Panel Angle

## Training Configuration

* Loss Function: MSELoss
* Optimizer: AdamW
* Scheduler: ReduceLROnPlateau
* Epochs: 80
* Batch Size: 64

---

# 📈 Feature Engineering

To better understand temporal patterns, cyclic encoding techniques are used.

## Hour Encoding

* hour_sin
* hour_cos

## Seasonal Encoding

* day_sin
* day_cos

These techniques help the model learn periodic environmental behaviors more effectively.

---

# 🖥️ User Interface

The user interface is built with Streamlit and fully customized using CSS.

## UI Features

* Glassmorphism design
* Solar-energy-inspired color palette
* Dynamic animations
* Professional sidebar
* Animated gear settings icon
* AI status loading system

---

# ⚙️ Installation & Setup

## 1. Clone the Repository

Open CMD or Terminal and run:

```bash id="r6k2mx"
git clone https://github.com/YOUR_USERNAME/solar-ai.git
```

Then enter the project folder:

```bash id="d9p4yt"
cd solar-ai
```

---

## 2. Install Required Libraries

Install dependencies using:

```bash id="h3n8cv"
pip install -r requirements.txt
```

Or install them manually:

```bash id="j8m2qa"
pip install streamlit torch numpy pandas matplotlib scikit-learn joblib
```

---

## 3. Run the Application

Start the Streamlit app:

```bash id="t5w9sa"
streamlit run app.py
```

---

## 4. Open the User Interface

After running the command:

* The application will automatically open in your browser
* The local application address will usually be:

```text id="x3q7lm"
http://localhost:8501
```

---

## 5. Required Project Files

The following files must exist in the root directory:

```text id="y6k2bt"
solar_lstm.pth
best_model.pth
scaler_X.pkl
scaler_y.pkl
config.pkl
style.css
model.py
utils.py
app.py
```

If any of these files are missing, parts of the system may fail to run correctly.

---

# 📦 Required Libraries

```txt id="m4p7ce"
streamlit
torch
numpy
pandas
matplotlib
scikit-learn
joblib
```

---

# 🌍 Real-World Applications

* Smart solar farms
* Solar tracking systems
* Renewable energy optimization
* IoT solar systems
* Intelligent energy management

---

# 🔥 Future Improvements

* Weather API integration
* Automatic GPS positioning
* Mobile application
* Energy analytics dashboard
* Cloud deployment
* Docker support
* Real-time performance analytics

---

# 📊 Model Evaluation

The model is evaluated using:

* MAE
* MSE
* RMSE
* R² Score

Additional solar tracking efficiency metrics are also implemented.

---

# 👨‍💻 Development Notes

This project was developed to combine artificial intelligence with renewable energy technologies and create a practical intelligent solar optimization system.

The entire UI and prediction pipeline were fully customized and designed for a production-like experience.

---

# 📜 License

This project was developed for educational and research purposes.

---

# ☀️ Solar AI

AI-powered prediction system for optimal solar panel angle
