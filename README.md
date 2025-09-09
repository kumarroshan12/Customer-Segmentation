# 🧠 Customer Segmentation Using Machine Learning

This project aims to segment customers based on their demographic and behavioral attributes using unsupervised and supervised machine learning techniques. It provides insights into customer groups that can be targeted with personalized marketing strategies.

## 📊 Dataset

The dataset used for this project includes the following features:

- `ID`: Unique identifier
- `Gender`: Male or Female
- `Ever_Married`: Marital status
- `Age`: Age of the customer
- `Graduated`: Educational qualification
- `Profession`: Type of profession
- `Work_Experience`: Years of experience
- `Spending_Score`: Customer's spending score (1-100)
- `Family_Size`: Number of family members
- `Var_1`: Categorical variable
- `Segmentation`: Target variable (A, B, C, D)


---

## 🧰 Tech Stack & Tools

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook / Google Colab
- Machine Learning Models:
  - K-Means Clustering
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost (optional)

---

## 📌 Project Structure

customer_segmentation/
├── data/
│ ├── raw/
│ ├── processed/
├── notebooks/
│ ├── EDA.ipynb
│ ├── clustering.ipynb
│ └── classification.ipynb
├── src/
│ └── utils.py
├── output/
│ └── segmentation_results.csv
├── README.md
└── requirements.txt

yaml
Copy
Edit

---

## 🔍 Key Steps

1. **Exploratory Data Analysis (EDA)**  
   - Handled missing values, data types, and outliers  
   - Visualized distributions, correlations, and feature relationships  

2. **Feature Engineering**  
   - Encoded categorical variables  
   - Normalized/Standardized numerical values  

3. **Clustering (Unsupervised Learning)**  
   - Used K-Means to group customers  
   - Determined optimal clusters using the Elbow method and Silhouette score  

4. **Classification (Supervised Learning)**  
   - Trained models to predict customer segments  
   - Evaluated using accuracy, precision, recall, and confusion matrix  

---

## 📈 Results

- Achieved **86% accuracy** with Random Forest (Replace with your actual score)
- Identified key features influencing segmentation: `Spending_Score`, `Age`, `Profession`, etc.

---

## 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/customer_segmentation.git
cd customer_segmentation

# Install dependencies
pip install -r requirements.txt

# Launch notebooks
jupyter notebook
