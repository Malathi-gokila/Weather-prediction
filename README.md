# 🌤 Weather Data Fetching & Temperature Prediction  

## 📌 Overview  
This **Streamlit-based** web application fetches **real-time weather data** using the OpenWeatherMap API and predicts **future temperatures** using a **linear regression model**.  

## ✨ Features  
✅ Fetches **real-time weather** data for a given city.  
✅ Displays **temperature, humidity, and weather conditions**.  
✅ Predicts **future temperatures** using **linear regression**.  
✅ User-friendly **Streamlit** interface.  

## 🔧 Requirements  
Ensure you have the following installed:  
- Python **3.x**  
- **Streamlit**  
- **Requests**  
- **Pandas**  
- **Scikit-learn**  

## 🚀 Installation  

1️⃣ Clone this repository:  
```bash
git clone https://github.com/Nandhu18786/Weather-Prediction.git
cd Weather-Prediction
```  

2️⃣ Install dependencies:  
```bash
pip install -r requirements.txt
```  

## ▶️ Usage  

1️⃣ Run the Streamlit app:  
```bash
streamlit run weather.py
```  

2️⃣ Enter the **city name** in the input field.  
3️⃣ View the **real-time weather** data and **predicted temperature trends**.  

## 🔑 API Key Setup  

To use the **OpenWeatherMap API**, obtain an **API key** from [OpenWeatherMap](https://openweathermap.org/api) and set it in your environment:  

```bash
export WEATHER_API_KEY='your_api_key_here'
```  

Or set it directly in the script:  

```python
API_KEY = 'your_api_key_here'
```  

## 📂 Project Structure  

```
📂 Weather-Prediction
├── weather.py         # Main Streamlit app script
├── requirements.txt   # Required Python libraries
├── README.md          # Documentation
```

