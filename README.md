# 🏠 Real Estate Price Predictor

> **IIT Jammu Summer Internship 2026 | Week 2 Project**  
> A machine learning-powered web application for predicting housing prices in Bengaluru with an interactive, modern UI.

---

## 📋 Overview

This project implements a **machine learning-based price prediction model** for residential properties in Bengaluru. Built with Flask as the backend and a responsive frontend, it provides an intuitive interface to estimate property values based on location, area, bedrooms, and bathrooms.

**Built by:** *Nikhil Sanjay Kumar Srivastava*  
**Duration:** IIT Jammu Summer Internship 2026 (Week 2)

---

## ✨ Features

- 🎯 **Accurate Predictions** – Mean Absolute Percentage Error (MAPE) of ~17%
- 🌙 **Dark Mode Support** – Seamlessly toggle between light and dark themes
- 📊 **Interactive Gauge Visualization** – Real-time gauge display with prediction confidence bands
- 🎚️ **Intuitive Sliders** – Smooth controls for area, bedrooms, and bathrooms
- 📍 **Location-Based Pricing** – Support for 200+ Bengaluru neighborhoods
- 🎨 **Modern UI** – Built with Bootstrap and custom CSS for superior aesthetics
- ⚡ **Responsive Design** – Works flawlessly on desktop, tablet, and mobile devices

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Backend** | Python 3.x, Flask |
| **ML Model** | Scikit-learn, Pandas, NumPy |
| **Frontend** | HTML5, Bootstrap 5.3, CSS3 |
| **Interactive Elements** | Vanilla JavaScript |
| **Data** | Bengaluru Housing Dataset (CSV) |

---

## 📁 Project Structure

```
.
├── app.py                          # Flask application entry point
├── Bengaluru_House_Data.csv        # Dataset with property prices
├── requirements.txt                # Python dependencies
├── Week2.ipynb                     # Jupyter notebook with model development
├── templates/
│   └── index.html                  # Main web interface
└── static/
    ├── css/
    │   └── style.css               # Custom styling (light & dark modes)
    └── js/
        └── app.js                  # Client-side interactivity
```

---

## 🚀 Quick Start

### Prerequisites
- Python 3.7+
- pip (Python package manager)

### Installation

1. **Clone or download the project:**
   ```bash
   cd "Jammu Summer School/Week 2/Lecture 3"
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv .venv
   ```

3. **Activate the virtual environment:**
   - **Windows (PowerShell):**
     ```powershell
     .\.venv\Scripts\Activate.ps1
     ```
   - **macOS/Linux:**
     ```bash
     source .venv/bin/activate
     ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the application:**
   ```bash
   python app.py
   ```

6. **Open in browser:**
   Navigate to `http://localhost:5000`

---

## 📊 Model Details

### Training Data
- **Dataset:** Bengaluru Housing Market Data
- **Features:** Location, Total Square Feet, Bedrooms, Bathrooms
- **Target:** Price in Lakhs (₹)
- **Records:** ~13,000 properties

### Model Performance
- **Algorithm:** Linear Regression / XGBoost (optimized for accuracy)
- **Mean Absolute Percentage Error (MAPE):** ~17%
- **Prediction Range:** Displayed with ±17% confidence band on gauge

### How Predictions Work
1. Select a location from 200+ Bengaluru neighborhoods
2. Adjust property parameters using interactive sliders
3. Click "Estimate Market Value"
4. Receive instant price prediction with confidence interval
5. Visual gauge displays the estimate in context of the price range

---

## 🎨 UI/UX Highlights

### Dark Mode
- 🌙 Automatic detection of system preferences
- 💾 Persistent theme selection in localStorage
- 🎯 Perfect contrast and readability in both modes

### Interactive Elements
- **Sliders** – Smooth range inputs with real-time feedback
- **Summary Box** – Live preview of selected parameters
- **Animated Gauge** – Smooth needle animation and arc visualization
- **Real-time Updates** – Form summary updates as you adjust values

### Responsive Design
- ✅ Desktop (1024px+)
- ✅ Tablet (768px–1023px)
- ✅ Mobile (<768px)

---

## 📈 How to Use

### Step 1: Select Location
Choose from the dropdown menu containing all major Bengaluru neighborhoods.

### Step 2: Adjust Parameters
Use the sliders to set:
- **Area** (300–8000 sqft)
- **Bathrooms** (1–8)
- **Bedrooms** (1–8 BHK)

### Step 3: Get Prediction
Click the blue "Estimate Market Value" button to receive:
- Predicted price in Lakhs
- Confidence band (±17% MAPE)
- Visual representation on the gauge

---

## 🔧 Configuration

### Available Dependencies
View all installed packages:
```bash
pip list
```

### Modifying the Model
Edit `app.py` to:
- Load a different pre-trained model
- Adjust prediction parameters
- Add new features or locations

---

## 🎓 Learning Outcomes

This project demonstrates:
- ✅ Machine Learning model deployment in production
- ✅ Full-stack web application development
- ✅ Frontend-backend integration
- ✅ User experience and interface design
- ✅ Data visualization techniques
- ✅ Version control and project management

---

## 📝 Notes

- All prices are in **Indian Rupees (₹)** and displayed in **Lakhs**
- The dataset includes properties from Bengaluru across all major neighborhoods
- Model accuracy varies by location and property type
- Predictions serve as estimates; actual market values may vary

---

## 🤝 Connect

- 🔗 **GitHub:** [nikhilsri8052-a11y](https://github.com/nikhilsri8052-a11y)
- 💼 **LinkedIn:** [Nikhil Srivastava](https://www.linkedin.com/in/nikhil-srivastava-b822a8325)

---

## 📄 License

This project was created as part of the IIT Jammu Summer Internship 2026 (Week 2) and is intended for educational purposes.

---

**Happy Predicting! 🏠✨**
