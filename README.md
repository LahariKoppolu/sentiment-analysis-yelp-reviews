# Sentiment Analysis of Yelp Business Reviews 📝🔍

This project performs sentiment analysis on Yelp customer reviews to classify opinions as **positive or negative**, and extract business insights using Natural Language Processing (NLP) techniques.

## 🚀 Project Highlights

- Cleaned and preprocessed 86,000+ Yelp reviews
- Visualized frequent words with WordClouds and frequency plots
- Vectorized text using **CountVectorizer** and **TF-IDF**
- Built and evaluated models using:
  - Multinomial Naive Bayes
  - Random Forest Classifier
- Achieved ~93% accuracy in sentiment classification

## 🛠️ Tools & Technologies
- Python, Pandas, NumPy
- scikit-learn, NLTK
- WordCloud, Seaborn, Matplotlib

## 📊 Example Output
![wordcloud](images/wordcloud_negative.png)
![bar](images/bar_positive_terms.png)

## 📁 Dataset
[Yelp Open Dataset](https://www.yelp.com/dataset)

## 🤖 Model Performance
| Model                  | Accuracy | Precision (Pos/Neg) |
|-----------------------|----------|---------------------|
| Multinomial Naive Bayes | 92.5%    | 96% / 82%           |
| Random Forest           | 88.9%    | 91% / 83%           |

## 📌 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
