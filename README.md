# Clinical Diagnosis Prediction App

## 📌 Overview
This application uses a **fine-tuned BERT model** to predict clinical diagnoses from patient notes. It processes clinical reports, extracts relevant information, and provides diagnostic suggestions to healthcare professionals.

## 🚀 Features
- **Fine-tuned BERT model** for clinical text analysis
- **Supports 20 different disease categories**
- **FastAPI backend** for efficient processing
- **PDF extraction capability** for clinical reports
- **User-friendly web interface** for report upload and diagnosis prediction

## 🛠 Installation
### 1️⃣ Clone the repository:
```sh
git clone https://github.com/TarunKumarRevelli/Clinical-Diagnosis-Prediction-App.git
cd Clinical-Diagnosis-Prediction-App
```

### 2️⃣ Install dependencies:
```sh
pip install -r requirements.txt
```

## 📌 Usage
### 1️⃣ Start the FastAPI server:
```sh
uvicorn main:app --reload
```
### 2️⃣ Open the web interface:
- Visit **[http://localhost:8000](http://localhost:8000)** in your browser.
- Upload a **clinical report (PDF format).**
- View the **predicted diagnosis** and associated **confidence scores.**

## 🔬 Model Details
- **Base Model:** BERT (`bert-base-cased`)
- **Fine-tuned on:** 5,000 clinical notes across 20 disease categories
- **Achieves high accuracy** on common conditions like **Type 2 Diabetes** and **Asthma**

## 📂 File Structure
```
Clinical-Diagnosis-Prediction-App/
│── main.py           # FastAPI application
│── model/            # Contains the fine-tuned BERT model
│── preprocessing/    # Text preprocessing scripts
│── static/           # CSS and JavaScript files for the web interface
│── templates/        # HTML templates for the web interface
│── requirements.txt  # Dependencies
│── README.md         # Project documentation
```

## 🤝 Contributing
Contributions to improve model accuracy or extend supported disease categories are welcome! To contribute:
1. **Fork** the repository.
2. Create a **new branch** (`feature-improvement` or `bugfix-xyz`).
3. **Commit your changes** with clear messages.
4. **Submit a pull request** for review.

## 📜 License
This project is licensed under the **MIT License**.

## 📧 Contact
For any queries, feel free to reach out:
- **Tarun Kumar Revelli** - tarun18177@gmail.com
- **GitHub:** [TarunKumarRevelli](https://github.com/TarunKumarRevelli)
