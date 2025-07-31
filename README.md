# AGRI_TECH_NAVIGATOR
### Farmer Friendly website provide all information to the farmer in local language also AI integreted ferure like crop recommendation, Fertilizer suggestion and plant disease identifier.
## Author - HARSHAD PRASHANT DESAI


# 🌿 Agri-Tech-Navigator - Precision Farming with ML & DL

A simple Machine Learning and Deep Learning-based web application that helps farmers with:
- ✅ **Crop Recommendation**
- ✅ **Fertilizer Suggestion**
- ✅ **Plant Disease Detection**

> 📺 **Featured on Krish Naik’s YouTube Channel**  
> 🔗 [Watch it here](#) *(Insert link if available)*

---

## ⚠️ Disclaimer
This is a **Proof of Concept (POC)** project.  
The datasets used here are limited and may not reflect real-world conditions.  
**Please do not make critical farming decisions based on this tool.**  
However, this project showcases how ML/DL can be integrated into **precision agriculture** when developed at scale using authentic and verified data.

---

## 💡 Motivation

Agriculture plays a crucial role in the economic development of countries like **India**, where a large part of the population depends on farming.

With advancements in **Machine Learning (ML)** and **Deep Learning (DL)**, it's now possible to enhance productivity, reduce manual effort, and optimize farming practices.

**Harvestify** is a project designed with three core features:

1. **Crop Recommendation** – Predict the most suitable crop based on soil nutrients and weather.
2. **Fertilizer Suggestion** – Suggest the right fertilizer based on nutrient balance and crop.
3. **Plant Disease Detection** – Detect plant diseases through leaf images and suggest cures.

---

## 📊 Datasets Used

- **Crop Recommendation:** Custom-built dataset
- **Fertilizer Suggestion:** Custom-built dataset
- **Plant Disease Detection:** PlantVillage dataset

---

## 📓 Notebooks

Check the training and preprocessing code on Kaggle:

- [Crop Recommendation Notebook](#)
- [Disease Detection Notebook](#)

---

## 🛠️ Built With

- Python
- Flask
- Scikit-learn
- TensorFlow / PyTorch
- OpenCV
- HTML, CSS, JavaScript (for frontend)
- Weather API (for temperature/humidity based on location)

---

## 🚀 Deployment

- **Hosted on:** [Heroku](#) *(Insert live URL here)*  
  _Note: App may take a minute to load due to free-tier hibernation._

---

## 💻 How to Use

### 🥦 Crop Recommendation System
- Input soil **N-P-K** values (Nitrogen, Phosphorous, Potassium), **state**, and **city**.
- System fetches temperature and humidity via weather API.
- Returns the best crop to grow.

> ℹ️ N-P-K values should represent the ratio, not absolute values.  
> Avoid using names of remote towns, stick to major cities for accuracy.

---

### 🌱 Fertilizer Suggestion System
- Enter N-P-K values of your soil and the crop name.
- The model tells if any nutrient is in excess or deficient.
- Suggests appropriate fertilizers.

---

### 🍃 Plant Disease Detection
- Upload an image of a **plant leaf**.
- The model detects whether it’s **healthy** or **diseased**.
- If diseased, it shows the cause and suggested cure.

> 🌾 Currently supports specific crops only.

---

## 🧑‍💻 Local Setup

Make sure `git` and `Anaconda`/`Miniconda` are installed.

### Clone the repository:

```bash
git clone -b deploy https://github.com/Gladiator07/Harvestify.git
cd Harvestify
