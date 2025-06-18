# 🎬 Movie Recommendation System

## 📌 Project Overview

The **Movie Recommendation System** is a machine learning-based application designed to provide personalized movie suggestions to users. By analyzing past user ratings and identifying patterns through collaborative filtering, the system generates accurate recommendations. It uses the popular **MovieLens dataset** and cosine similarity metrics to suggest movies similar to a user's preferences.

This project is ideal for integration into streaming services, movie review platforms, or as a standalone movie catalog system.

---

## 🚀 Getting Started

To run this project locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/RavishankarDuMCA10/Movie-Recommendation-System.git
cd movie-recommendation-system
```

### 2. Install Dependencies

It is recommended to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Then install the required packages:

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is not available, manually install:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook Movie-Recommendation-System.ipynb
```

---

## 🗂️ Project Structure and Code

```
movie-recommendation-system/
│
├── Movie-Recommendation-System.ipynb  # Main notebook with data processing & recommendation logic
├── README.md                          # Project overview and usage
├── requirements.txt                   # Dependencies (optional)
└── data/                              # Folder containing the MovieLens dataset
```

---

## 📊 Data

The system uses the **MovieLens 100k** dataset, which includes:

- User IDs and movie ratings
- Movie metadata (titles, genres)
- Approximately 100,000 ratings from 943 users on 1,682 movies

You can download the dataset from [GroupLens](https://grouplens.org/datasets/movielens/100k/).

Ensure the dataset files (e.g., `u.data`, `u.item`) are placed in a `data/` folder relative to the notebook.

---

## 🧠 Model and Training

This project uses **memory-based collaborative filtering**, specifically **item-based filtering**, with the following methodology:

- **User-Item Matrix**: Constructed using pivot tables
- **Cosine Similarity**: Calculated between items (movies)
- **Recommendation Logic**: For a given user, suggest items most similar to the ones they've rated highly

> No complex model training is required as this is a similarity-based method.

---

## ⚙️ Advanced Usage

- 🎯 **Custom User Input**: You can input any user ID present in the dataset and get recommendations
- 🔄 **Dynamic Updates**: To integrate with real-time data, periodically recompute the similarity matrix
- 📈 **Visualization**: The notebook includes exploratory data analysis and visualizations to understand rating distributions and trends

---

## 🧰 Technology Used

- **Python 3.x**
- **Jupyter Notebook**
- **pandas** – for data manipulation
- **scikit-learn** – for cosine similarity
- **NumPy** – numerical computations
- **matplotlib / seaborn** – data visualization

---

## 📬 Contact Information

**Ravi Shankar Kushwaha**  
🔗 LinkedIn: [linkedin.com/in/ravi-shankar-k-45a77224/](https://www.linkedin.com/in/ravi-shankar-k-45a77224/)
