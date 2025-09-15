# 🌾 Crop Disease Detection & Advisory Dashboard

This is a **Streamlit-based web application** for detecting crop diseases from leaf images and providing treatment advice.  
⚠️ *This is a demo template. Replace with your own trained ML/DL model for real predictions.*

---

## 🚀 Features
- Upload leaf images (`.jpg`, `.jpeg`, `.png`)
- Detect diseases such as:
  - Healthy
  - Tomato Mosaic Virus
  - Powdery Mildew
  - Leaf Blight
- Get **confidence score (%)** and **treatment recommendations**
- Track and visualize **prediction history**
- Simple, lightweight, and easy to extend with your own model

---

## 📦 Installation

1. Clone this repository or copy the code files.
2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate    # On Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

Then open your browser at: **http://localhost:8501**

---

## 🗂 Project Structure

```
📂 crop-disease-detection
 ├── app.py               # Main Streamlit app
 ├── requirements.txt     # Dependencies
 └── README.md            # Project documentation
```

---

## 📊 Example Output

- Upload a tomato leaf image
- App predicts: **Powdery Mildew (92.3%)**
- Recommendation: 🌿 Use sulfur-based fungicides. Avoid overhead irrigation.

---

## ⚠️ Disclaimer

This app is **for educational/demo purposes only**.  
It should **not** be used as a substitute for professional agricultural or medical advice.
---
