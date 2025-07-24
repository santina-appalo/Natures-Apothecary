# Nature’s Apothecary 🌿

**Nature’s Apothecary** is a holistic wellness web application that integrates ancient herbal medicinal systems with modern technologies such as interactive 3D models and machine learning. This project provides a user-friendly platform to explore herbal knowledge, visualize medicinal plants in 3D, and receive AI-powered herb recommendations based on symptoms.

---

## 🔗 Live Demo

[Insert deployment link here if available]

---

## 🧠 Features

- 🌱 **Five Traditional Healing Systems**
  - Ayurveda, Unani, Siddha, Homeopathy, and Naturopathy.
  - Each system includes detailed herb profiles, benefits, and historical uses.

- 🧬 **Interactive 3D Models**
  - Herbs are visualized using embedded **Spline-rendered 3D models**.
  - Enhances learning through realistic, manipulable plant structures.
  
- 🖼️ **Multiple Image Galleries**
  - Each herb page contains a gallery with high-resolution images to improve recognition and identification.

- 🧪 **Machine Learning-Based Recommendation**
  - Users can input their symptoms, and the backend **Flask app with ML model** will suggest relevant herbs as potential remedies.

- 💻 **Responsive Design**
  - Clean and dynamic UI built with **HTML, CSS, JavaScript**, and **Flask** backend.
  - Works well across desktop and mobile browsers.

---

## 📷 Screenshots

> Replace these placeholders with real screenshots

### Home Page
![Home Page](screenshots/home.png)

### Ayurveda Page with 3D Model
![Ayurveda Page](screenshots/ayurveda-3d.png)

### ML Symptom Input Page
![Symptom Checker](screenshots/ml-form.png)

---

## 🛠️ Tech Stack

| Frontend        | Backend        | 3D Models     | Machine Learning    |
|----------------|----------------|---------------|---------------------|
| HTML/CSS/JS     | Flask (Python) | Blender + Spline | Scikit-learn (Pickle model) |

---

## 🧪 How It Works

### 1. Herbal Exploration
- Users navigate through traditional medicinal systems.
- Each page includes a carousel of herbs with 3D models and details.

### 2. Symptom Checker (ML Integration)
- A form allows users to input symptoms.
- The Flask backend processes the input and uses a trained model to predict and suggest matching herbs.

---

## 📁 Project Structure

```bash
project/
├── templates/
│   └── forest_fire.html        # Main page with input form
├── static/
│   └── styles.css              # Custom styling
├── Page1.html                  # Landing page with sliders
├── ayurveda.html               # Example of a system page
├── App.py                      # Flask backend with ML model
├── model.pkl                   # Pickled ML model
├── README.md                   # This file
└── screenshots/                # Folder for screenshots

---

## 🚀 Setup Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/natures-apothecary.git
cd natures-apothecary
```

2. **Install Dependencies**
```bash
pip install flask numpy scikit-learn
```

3. **Run the Flask Server**
```bash
python App.py
```

4. **View in Browser**
```
Visit http://127.0.0.1:5000 in your browser
```

---

## 📌 Future Enhancements

- User authentication and personalized herbal dashboards
- Integration of symptom severity & history tracking
- Exportable PDF reports of recommended herbs
- Mobile app version

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
