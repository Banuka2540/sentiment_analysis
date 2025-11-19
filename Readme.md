# 📝 Sentiment Analysis Web App  
A lightweight Machine Learning–powered web application that predicts whether a given text input expresses **Positive** or **Negative** sentiment.  
Built using Python, scikit-learn, and a simple Flask-based web interface.

---

## 🚀 Features
- 🔍 **Real-time sentiment prediction**  
- 🤖 **ML pipeline** with preprocessing + model training  
- 🌐 **Clean Flask web interface**  
- 📊 Trained on a labeled dataset (stored in `Artifacts/` & `anaconda_projects/db/`)  
- 📂 Well-structured project layout for easy understanding and modification

---

## 📁 Project Structure

├── Artifacts/ # Dataset + exported ML model
├── Notebooks/ # Jupyter notebooks (training, evaluation, EDA)
├── Static/ # CSS and static assets for the web app
├── templates/ # HTML templates for Flask UI
├── anaconda_projects/db/ # Dataset and config files
├── app.py # Main Flask app
├── helper.py # ML pipeline + model loading helpers
├── requirements.txt # All project dependencies
└── README.md # Project documentation


---

## 🧠 How It Works  
1. User enters any sentence or phrase.  
2. The app preprocesses the text (cleaning, tokenizing, vectorizing).  
3. The trained ML model predicts whether it's **Positive** or **Negative**.  
4. Result is displayed instantly on the web interface.  

Simple, fast, and accurate — exactly how a modern ML tool should be 😎

---

## 🔧 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Banuka2540/sentiment_analysis.git
cd your-repo-name

pip install -r requirements.txt

python app.py
