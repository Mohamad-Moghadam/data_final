# 📱 Google Play Store Apps — Data Analysis & Visualization

A comprehensive exploratory data analysis (EDA) of the Google Play Store app ecosystem using Python, Pandas, Matplotlib, and Seaborn. This project cleans, analyzes, and visualizes trends across **10,000+ apps** and **64,000+ user reviews** to uncover actionable insights about app categories, pricing, ratings, user sentiment, and market dynamics.

---

## 📂 Datasets

| File | Description | Records |
|------|-------------|---------|
| `googleplaystore.csv` | App metadata (category, rating, size, installs, price, etc.) | ~10,800 apps |
| `googleplaystore_user_reviews.csv` | User reviews with sentiment labels and polarity scores | ~64,200 reviews |

&gt; **Source:** [Kaggle — Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook / JupyterLab / VS Code

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/google-playstore-analysis.git
cd google-playstore-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook playstore_analysis.ipynb
