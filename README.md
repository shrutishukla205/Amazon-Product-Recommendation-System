  # Amazon-Product-Recommendation-System
A Machine Learning-based personalized product recommendation system using User-Based Collaborative Filtering.
# 🛒 Amazon Product Recommendation System

## 📌 Overview

The **Amazon Product Recommendation System** is a Machine Learning project that recommends products to users based on their preferences and historical rating patterns.

This project implements **User-Based Collaborative Filtering**, which identifies users with similar interests and uses their ratings to predict products that a selected user may prefer.

The system generates a personalized list of the Top 10 recommended products while filtering out products that the selected user has already rated.

## 🎯 Objectives

- Analyze user-product rating patterns.
- Build a User-Product Rating Matrix.
- Calculate similarity between users.
- Identify users with similar preferences.
- Predict ratings for unrated products.
- Generate personalized Top 10 recommendations.
- Visualize recommendation scores.

## 🛠️ Technologies & Tools

| Technology   | Application                              |
| ------------ | ---------------------------------------- |
| Python       | Core programming                         |
| Pandas       | Data manipulation                        |
| NumPy        | Numerical computations                   |
| Scikit-learn | Similarity calculations and ML utilities |
| Matplotlib   | Data visualization                       |
| Seaborn      | Statistical visualization                |
| Google Colab | Development environment                  |

## 🧠 Recommendation Algorithm

### User-Based Collaborative Filtering

User-Based Collaborative Filtering is a recommendation technique that suggests products based on the preferences of users with similar interests.

Instead of recommending products only based on their popularity, the system considers the rating patterns of similar users.

### Working Process

1. **User-Product Matrix:** Creates a matrix containing user ratings for different products.
2. **Similarity Calculation:** Calculates similarity between users based on their rating patterns.
3. **Similar User Identification:** Selects users with similar preferences.
4. **Weighted Rating Prediction:** Calculates predicted ratings using similarity scores.
5. **Product Filtering:** Removes products already rated by the selected user.
6. **Recommendation Ranking:** Sorts products by predicted scores and displays the Top 10.

## ⚙️ Project Workflow

```text
       Amazon Ratings Dataset
                 |
                 ▼
        Data Preprocessing
                 |
                 ▼
        User-Product Matrix
                 |
                 ▼
       User Similarity Matrix
                 |
                 ▼
       Similar User Selection
                 |
                 ▼
       Weighted Rating Prediction
                 |
                 ▼
       Product Filtering
                 |
                 ▼
       Top 10 Recommendations
                 |
                 ▼
        Results Visualization
                 |
                 ▼
             CSV Export
```

## ✨ Key Features

- Personalized product recommendations.
- User similarity-based analysis.
- Weighted rating prediction.
- Filtering of previously rated products.
- Top 10 product ranking.
- Recommendation score visualization.
- Export recommendations into CSV format.

## 📊 Recommendation Results

The system generates personalized product recommendations for a selected user.

**Sample Output:**

| Product ID | Predicted Score |
| ---------- | --------------: |
| B00004TDN2 |        1.004059 |
| B00004VUGJ |        0.966156 |
| B00004SB92 |        0.920264 |
| B00004S9AK |        0.887471 |
| B00004TS16 |        0.887471 |

*Sample results from the generated recommendation output.*

## 📉 Model Evaluation

The project includes the following recommendation evaluation metrics:

- Precision\@10
- Recall\@10

**Evaluation Status:** The initial evaluation returned 0.0 for both metrics. A proper evaluation using held-out test data is required before drawing conclusions about recommendation performance.

## 📁 Repository Structure

```text
Amazon-Product-Recommendation-System/
│
├── banner.png
│
├── Amazon_Product_Recommendation.ipynb
│
├── ratings_Electronics.csv
│
├── amazon_product_recommendations.csv
│
└── README.md
```

## 🚀 Installation & Execution

### 1. Clone the Repository

```bash
git clone https://github.com/shrutishukla205/Amazon-Product-Recommendation-System.git
```

### 2. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 3. Open the Notebook

Open `Amazon_Product_Recommendation.ipynb` using Google Colab.

### 4. Upload the Dataset

Upload `ratings_Electronics.csv` to your Google Colab environment.

### 5. Execute the Notebook

Run all notebook cells sequentially to preprocess the data, calculate user similarities, predict product ratings, and generate recommendations.

## 🔮 Future Enhancements

- Implement proper train-test evaluation.
- Improve recommendation quality.
- Explore Item-Based Collaborative Filtering.
- Experiment with Matrix Factorization techniques.
- Develop an interactive recommendation dashboard using Streamlit.
- Integrate product details and product images.

## 👩‍💻 Author

**Shruti Shukla**

[GitHub Profile](https://github.com/shrutishukla205)

---

\<p align="center">
&#x20; Made with ❤️ using Python & Machine Learning
\</p>
