# Rnn_imdb
# 🎬 Movie Review Sentiment Analyzer

---

## 📌 Project Overview

This project uses a **deep learning model built with TensorFlow** to classify movie reviews as **positive** or **negative**.  
It was trained on the **IMDB dataset** and predicts the sentiment of any user-provided review.  
A **Streamlit web app** provides a simple and interactive interface to use the model.

---

## 🚀 How to Run in Google Colab (⚡ Easy 3-Step Setup)

### 1. Install Streamlit:
```bash
!pip install streamlit -q
```  
2. (Optional) Check your public IP:
```
!wget -q -O - ipv4.icanhazip.com
```
3. Run the Streamlit app using LocalTunnel:
```
!streamlit run app.py & npx localtunnel --port 8501
```
## 🔗 You’ll get a public URL to interact with the app from anywhere.

📁 Files in this Repository
app.py – 🖥️ Streamlit application file

sentiment_rnn_model.keras – 🧠 Trained TensorFlow RNN model

reqirements.txt – 📦 Required Python packages

README.md – 📖 You're reading it!

## ✅ Key Features
✨ Accepts user-input movie reviews via text box
✨ Predicts sentiment and displays:
    ✔️ Positive 😊
    ❌ Negative 😞
✨ Fast testing inside Colab
✨ Public interface using LocalTunnel

📌 Notes
🧪 This app is designed for quick prototyping and testing in Colab.

🌐 To deploy publicly (e.g., Streamlit Cloud or HuggingFace Spaces), first push all files to GitHub.

🖼️ App Interface (Sample Screenshot)

## Output

<img width="1114" height="589" alt="image" src="https://github.com/user-attachments/assets/3ae11060-b5cf-458f-aaa2-07bfd9178c03" />


