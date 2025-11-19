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

## 🧰 Tech Stack

### **Frontend**
- HTML5  
- CSS3 (in `/Static` folder)

### **Backend**
- Python 3  
- Flask 

### **Machine Learning**
- scikit-learn  
- NLP preprocessing (tokenization, vectorization)  
- Pipelines & model persistence  

### **Tools / Environment**
- Jupyter Notebook (model training & experimentation)
- Git & GitHub  
- VS Code 

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
