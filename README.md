# 🌾 Agri Tech Navigator – Empowering Farmers with ML & DL 🚜

A multilingual, intelligent agriculture assistant using **Machine Learning** and **Deep Learning**, enabling:
- ✅ **Crop Recommendation**
- ✅ **Fertilizer Suggestion**
- ✅ **Plant Disease Detection**
- ✅ **Government Scheme Guidance**
- ✅ **Modern Farming Technique Insights**
- ✅ **Marketplace Info** – for price insights

🌐 **Live App:** [agri-tech-navigator.onrender.com](https://agri-tech-navigator.onrender.com)  
💻 **GitHub Repo:** [github.com/harshaddesai04/AGRI_TECH_NAVIGATOR](https://github.com/harshaddesai04/AGRI_TECH_NAVIGATOR)

---

## ⚠️ Disclaimer

This is a **Proof of Concept (POC)** built for educational and demonstration purposes.  
The recommendations and data may not cover all agricultural conditions.  
Do not use this as the sole decision-making tool for critical farming activities.

---

## 🎯 Key Features

### 🥦 Crop Recommendation  
- **Inputs:** Soil **NPK**, **pH**, **Rainfall**, **Location** (State & City)  
- **Model:** Trained using Random Forest (Scikit-learn)  
- **Output:** Best crop suitable for the current condition  
- **Weather Integration:** Fetches temperature and humidity using Weather API  

### 🌱 Fertilizer Suggestion  
- **Inputs:** NPK levels and **Target Crop**  
- **Logic:** Rule-based approach based on nutrient balance  
- **Output:** Suggests which nutrient is lacking or excessive and recommends a fertilizer

### 🍃 Plant Disease Detection  
- **Input:** Upload an image of a leaf  
- **Model:** PyTorch CNN trained on the PlantVillage dataset  
- **Output:** Detects disease (if any) and provides cure or suggestion

### 📜 Government Schemes  
- Provides central and **state-specific schemes** useful to farmers  
- There are different schemes from various departments, and information is scattered across documents and websites.  
- I collected all the key scheme-related documents and website links into **a single, organized page** for farmer convenience.

### 🚜 Modern Farming Techniques  
- Explains technologies like **Hydroponics**, **Aeroponics**, **Hybrid Seeds**, etc.  

### 🌍 Multilingual Support  
- Integrated with **Google Translate dropdown**  
- Allows farmers to view the site in **multiple Indian languages**

---

## 📊 Tech Stack

| Layer       | Technologies                          |
|-------------|----------------------------------------|
| Backend     | Flask, Python                          |
| ML/DL       | Scikit-learn, PyTorch, Pandas, NumPy   |
| Frontend    | HTML, CSS, Bootstrap, JavaScript       |
| Image Tools | OpenCV, PIL                            |
| API         | Weather API (OpenWeatherMap), Google Translate API |
| Deployment  | Render.com                             |

---

## 📦 Project Structure

```plaintext
AGRI_TECH_NAVIGATOR/
│
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── city/
│
├── templates/
│
├── model/
│
├── utils/
`````
## 🚀 How to Run Agri Tech Navigator Locally

### 1. 📂 Clone the repository
```bash
git clone https://github.com/harshaddesai04/AGRI_TECH_NAVIGATOR.git
cd AGRI_TECH_NAVIGATOR```
```
### 2. 🐍 Create a virtual environment 
```bash
python -m venv harshad
harshad\Scripts\activate```
```
### 3. 📦 Install dependencies
```bash
pip install -r requirements.txt
```
### 4. ▶️ Run the Flask application
```bash
python app.py
```
### 5. 🌐 Open your browser and visit
```bash
http://127.0.0.1:5000
```
## 📞 Contact
💼 **LinkedIn:** [https://www.linkedin.com/in/Harshad-Desai/](https://www.linkedin.com/in/Harshad-Desai/)





