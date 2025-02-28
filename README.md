# 🩺 Heart Stroke Predictor  

## 📌 Project Overview  
The **Heart Stroke Predictor** is a machine learning-based application designed to predict the likelihood of a heart stroke based on various health parameters. The system analyzes patient information such as age, gender, medical history, and lifestyle habits to estimate stroke risk using predictive algorithms. The goal is to provide early warning and preventive measures to reduce the occurrence of strokes.  

## 🚀 Features  
- 📊 **Predicts Stroke Risk** using ML models like Logistic Regression.  
- 📈 **Probability-based Risk Assessment** (e.g., 78% risk of stroke).  
- 🏥 **Health Advisory System** for lifestyle modifications and prevention.  
- 🌎 **Recommends Nearby Cardiologists** for high-risk users.  
- 🔍 **Interactive Web Interface** for easy usage.  

## 🏗️ Tech Stack  
### 📌 Machine Learning  
- **Scikit-learn** – For data preprocessing and model training  
- **NumPy & Pandas** – For data handling and analysis  

### 📌 Web Development  
- **Django** – For backend development  
- **HTML, CSS, JavaScript** – For frontend interface  

### 📌 Data Visualization  
- **Matplotlib & Seaborn** – For graphical insights  

## ⚙️ Implementation Steps  
1. **Data Collection & Preprocessing**  
   - Handles missing values and normalizes data.  
   - Extracts relevant features like blood pressure, cholesterol levels, etc.  
2. **Feature Selection**  
   - Identifies key medical and lifestyle factors contributing to stroke risk.  
3. **Model Training**  
   - Trains a **Logistic Regression Model** for stroke prediction.  
4. **Model Evaluation**  
   - Uses accuracy, precision, recall, and F1-score for validation.  
5. **Web App Development**  
   - A user-friendly interface for predictions.  

## 🖥️ How to Run the Project  
### 🔧 Prerequisites  
- Python (>=3.8)  
- Required Libraries: Install using  
  ```bash
  pip install -r requirements.txt
  ```
- Django Framework  

### ▶️ Running the Project  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/heart-stroke-predictor.git
   cd heart-stroke-predictor
   ```
2. Run the Django server:  
   ```bash
   python manage.py runserver
   ```
3. Open `http://127.0.0.1:8000/` in your browser.  

## 📌 Results  
- Displays a **probability score** indicating stroke risk.  
- Offers **preventive suggestions** based on risk level.  
- Allows users to store **previous records** for tracking.  

## 🔮 Future Enhancements  
- 📲 Integration with **wearable devices** for real-time health monitoring.  
- 🔬 Inclusion of **deep learning models** for better accuracy.  
- 🌍 Expansion of dataset for **global applicability**.  

## 👥 Contributors  
- [Deepak Reddy](https://github.com/deepakreddyn)  
- [Neha Sadhvi](https://github.com/NehaSadhvi1904)  

