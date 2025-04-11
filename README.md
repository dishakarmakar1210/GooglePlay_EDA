# 📊 Google Play Store Data Analysis

This project performs an Exploratory Data Analysis (EDA) on the Google Play Store dataset. The goal is to understand trends and patterns among apps, including ratings, genres, pricing, size, and more. This notebook provides insights that can be useful for developers, marketers, and app users.

## 📁 Dataset

The dataset contains attributes of various apps published on the Google Play Store, such as:

- App name
- Category
- Rating
- Reviews
- Size
- Installs
- Type (Free/Paid)
- Price
- Content Rating
- Genres
- Last Updated
- Android Version

> 📌 *The dataset was preprocessed to clean and handle missing, incorrect, or inconsistent data before the analysis.*

## 🔍 Key Objectives

- Clean and preprocess the dataset
- Visualize app distribution by category
- Identify popular app genres
- Analyze app ratings and reviews
- Understand pricing and type (Free vs Paid)
- Observe app sizes and their relationship with ratings and installs

## 📊 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📌 Highlights of Analysis

- 📈 Most apps on the Play Store are free.
- 🌟 Categories like `TOOLS`, `FAMILY`, and `GAME` dominate in app count.
- 💵 Paid apps are a small fraction and pricing varies widely.
- 📝 Reviews and Installs follow a skewed distribution, with a few apps dominating.
- 🔢 Rating distributions show most apps have ratings between 4.0 and 4.5.
- 📱 Popular genres include Tools, Entertainment, and Productivity.

## 📂 Project Structure

```
GooglePlay_EDA/
├── GooglePlay.ipynb       # Jupyter notebook with complete EDA
├── README.md              # Project readme file
```

## ✅ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/dishakarmakar1210/GooglePlay_EDA.git
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook GooglePlay.ipynb
   ```

## 📌 Future Enhancements

- Add time-based analysis (e.g., trends over updates)
- Build a predictive model to estimate app success
- Deploy insights via an interactive dashboard (e.g., Power BI, Streamlit)

## 🙌 Acknowledgements

Dataset inspired by open sources available for educational and analytical purposes.

---
