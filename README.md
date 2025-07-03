# CleanTech: Transforming Waste Management with Transfer Learning

A deep learning-based web application that classifies waste images into **Biodegradable**, **Recyclable**, or **Trash** using a fine-tuned VGG16 model. Built as part of the **SmartInternz CleanTech project**, this system promotes sustainable waste segregation through intelligent automation.

📁 **Documents & Reports**  
All supporting documents and reports are available in this [Google Drive folder](https://your-drive-link-here).

---

## 🧠 Project Overview

- **Goal**: Automate real-time waste classification to support efficient urban waste handling.
- **Model**: Pre-trained **VGG16** with custom classification layers.
- **Interface**: Flask-based web app with a simple HTML frontend.

---

## 📂 Project Structure

w_flask/ ├── app.py # Flask backend ├── vgg16_model.keras # Trained model ├── templates/ │ ├── index.html # Upload form │ └── result.html # Prediction display ├── static/ │ └── uploads/ # Uploaded images └── train_model.ipynb # Model training notebook


---

## ⚙️ Setup Instructions

### ✅ Prerequisites
- Python 3.x
- pip or conda

### 📦 Install Dependencies
```bash
pip install flask tensorflow pillow
cd w_flask
python app.py

Then open your browser at http://127.0.0.1:5000/

🎥 Demo Video
Watch the working demo here

🙋‍♂️ Developed By
Your Name SmartInternz Virtual Internship Program July 2025

📜 License
This project is for educational purposes under the SmartInternz program.


---

Let me know if you want me to plug in your actual name, college, or demo video link—and I’ll finalize it for you! Want to add a flowchart or screenshot section too? I can help with that.
