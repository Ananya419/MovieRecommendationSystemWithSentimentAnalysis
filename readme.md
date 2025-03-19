
# 🎬 Movie Recommendation System with Sentiment Analysis  

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)  
![Surprise](https://img.shields.io/badge/Surprise-1.1.4-green.svg)  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.6.1-orange.svg)  

## 📌 Overview  

This project is a **Movie Recommendation System** using the **MovieLens dataset**. It employs **Singular Value Decomposition (SVD)** from the `Surprise` library to make personalized movie recommendations based on user ratings. Additionally, a **Sentiment Analysis module** is integrated to analyze user reviews and improve recommendations further.

---

## 🚀 Features  

✅ **Personalized Movie Recommendations** using SVD  
✅ **MovieLens Dataset** integration  
✅ **Cross-Validation & RMSE Calculation** for model evaluation  
✅ **Sentiment Analysis** of user reviews using `TextBlob`  
✅ **Scalable & Extendable** for additional recommendation techniques  

---

## 📂 Dataset  

The project uses the **MovieLens Small Dataset** provided by [GroupLens](https://grouplens.org/datasets/movielens/).  

- `movies.csv` - Movie metadata (ID, title, genres)  
- `ratings.csv` - User ratings (UserID, MovieID, Rating, Timestamp)  

Dataset is automatically downloaded and extracted in the script.

---

## 🛠 Installation  

### 🔹 Prerequisites  

Ensure you have Python 3.11+ installed.  

### 🔹 Install Dependencies  

```bash
pip install numpy pandas scikit-learn surprise textblob
```

To ensure `TextBlob` works correctly, download the necessary NLP corpora:

```bash
python -m textblob.download_corpora
```

---

## 📖 Usage  

### 🔹 1. Clone the Repository  

```bash
git clone https://github.com/Ananya419/MovieRecommendationSystemWithSentimentAnalysis
cd movie-recommendation-system
```

### 🔹 2. Run the Main Script  

```bash
python main.py
```

### 🔹 3. Get Movie Recommendations  

Modify `user_id` in the script to get recommendations:

```python
print(get_recommendations(user_id=5, n=5))
```

---

## 📊 Model Performance  

The model is evaluated using **Root Mean Squared Error (RMSE)**:

```
RMSE: 0.485
```

Lower RMSE indicates better prediction accuracy.

---

## 💡 Future Enhancements  

🔹 **Hybrid Recommendation** (Collaborative + Content-Based)  
🔹 **More Advanced NLP Techniques for Sentiment Analysis**  
🔹 **Web Interface using Flask or Streamlit**  

---

## 👨‍💻 Contributing  

Contributions are welcome! If you'd like to improve this project:  

1. Fork the repository  
2. Create a new branch (`feature-new-feature`)  
3. Commit your changes  
4. Push to the branch  
5. Create a **Pull Request**  

---


## 📞 Contact  

📧 Email: your.email@example.com  
🚀 GitHub: [Ananya419](https://github.com/Ananya419)  


