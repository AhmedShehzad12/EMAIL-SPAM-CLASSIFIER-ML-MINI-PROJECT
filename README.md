# 📧 Email Spam Classifier — AI/ML Mini Project

A Machine Learning web application that classifies **SMS/Email messages as Spam or Ham (Not Spam)** using Natural Language Processing (NLP) and a trained classification model. Built with **Streamlit** for an interactive user interface.

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikitlearn)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🧠 About the Project

Spam messages are one of the biggest problems in digital communication. This project uses **Natural Language Processing (NLP)** techniques and a **Machine Learning classifier** to automatically detect whether a given message is **Spam** or **Ham (legitimate)**.

The model is trained on a labeled SMS dataset, converted into numerical features using **TF-IDF Vectorization**, and served through a clean **Streamlit** web interface where users can type any message and get an instant prediction.

---

## 🎬 Demo

🔗 **Live Demo:** _Coming Soon / Add your deployed link here_

**Try it locally:**
```bash
Project Structure

EMAIL-SPAM-CLASSIFIER-ML-MINI-PROJECT/
│
├── app.py                          # Streamlit web application
├── sms-spam-detection.ipynb        # Model training notebook
├── model.pkl                       # Trained ML model
├── vectorizer.pkl                  # TF-IDF vectorizer
├── spam.csv                        # Dataset (SMS Spam Collection)
├── requirements.txt                # Python dependencies
├── nltk.txt                        # NLTK resources required
├── setup.sh                        # Setup script (for deployment)
├── Procfile                        # Deployment config (Heroku/Render)
├── README.md                       # Project documentation
├── .gitignore                      # Git ignore rules
│
├── AI project ppt.pptx             # Project presentation
└── ai project report group 9.pdf   # Detailed project report
