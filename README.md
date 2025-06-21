# 📦 eCommerce behavior data from multi category store

An advanced analysis of eCommerce customer behavior using machine learning and deep learning models on real-world data from a large multi-category online store.

## Dataset

**Source**: [Kaggle Dataset](https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store)

- **Size**: ~285 million events over 7 months (Oct 2019 - Apr 2020)
- **Event Types**:
  - `view` - Product viewed
  - `cart` - Added to cart
  - `remove_from_cart` - Removed from cart
  - `purchase` - Purchased product
- **Features**:
  - `event_time`, `event_type`, `product_id`, `category_id`, `category_code`
  - `brand`, `price`, `user_id`, `user_session`

## 🎯 Objective

Predict customer behavior (view, add to cart, purchase) during online shopping sessions using time series forecasting, machine learning, and deep learning.

---

## 🛠️ Workflow

### 1️⃣ Data Preprocessing
- Missing values imputation
- Linear interpolation for gaps
- Detrending & deseasonalization
- Train/Test Split (80/20)

### 2️⃣ Visualization
- Price distribution (Boxplots, Histograms, KDE)
- Event frequency over time
- Seasonal decomposition (Additive & Multiplicative)
- ACF & PACF plots for time dependencies

---

## 🤖 Models Used

### Machine Learning Models
| Model                | Accuracy |
|----------------------|----------|
| Random Forest        | 50%      |
| Logistic Regression  | 43%      |
| CatBoost             | 50%      |
| XGBoost              | 50%      |

### Deep Learning Models
| Model                | Accuracy  |
|----------------------|-----------|
| LSTM                 | 96.05%    |
| GRU                  | **96.06%** |
| Transformer          | 96.05%    |
| Temporal CNN (TCN)   | 96.05%    |

---

## ⚙️ Optimization
- **ML Models**: Grid Search, Random Search
- **DL Models**: Adam Optimizer, Dropout, Label Encoding
- Evaluation with Confusion Matrix, Accuracy, Precision, Recall, F1-Score

---

## 📊 Results

- ✅ **Best Machine Learning Model**: XGBoost (50%)
- ✅ **Best Deep Learning Model**: GRU (**96.06%**)
- Deep learning models significantly outperformed machine learning models in predictive accuracy.

---

## 📝 Conclusion

Combining **time series forecasting**, **machine learning**, and **deep learning** techniques provides a **robust predictive system** for understanding customer behavior in eCommerce. GRU showed the best balance between accuracy and efficiency.

---

## 📚 References

- Dataset: [Open CDP Project](https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store)
- Special thanks to REES46 Marketing Platform for providing the dataset.


