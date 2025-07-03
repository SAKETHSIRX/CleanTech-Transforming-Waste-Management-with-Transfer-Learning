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
pip install tensorflow flask numpy matplotlib

Run the Application

cd w_flask
python3 app.py

Then open your browser at http://127.0.0.1:5000/
🧪 Model Summary

    Base model: VGG16 (imagenet weights, without top)

    Added Layers: Flatten → Dropout → Dense (softmax)

    Accuracy:

        Training: 92.3%

        Validation: 90.6%

        Fine-tuned: 91.2%

📸 Sample Predictions

    Plastic Bottle → Recyclable

    Banana Peel → Biodegradable

    Styrofoam Cup → Trash

📈 Future Enhancements

    Add more waste categories (metal, glass, e-waste)

    Integrate smart bin sensors

    Deploy on cloud/edge devices

    Add mobile support

---

Let me know if you want me to plug in your actual name, college, or demo video link—and I’ll finalize it for you! Want to add a flowchart or screenshot section too? I can help with that.
