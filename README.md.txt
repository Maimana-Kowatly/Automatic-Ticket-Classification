# Customer Complaint Classification using NLP

## Project Overview
Customer complaints are crucial for financial companies as they highlight areas needing improvement in their products and services. Efficient resolution of these complaints minimizes customer dissatisfaction and enhances retention. However, manually categorizing complaints is time-consuming and inefficient as customer bases grow.

This project aims to automate customer support ticket classification using **Natural Language Processing (NLP)** and **machine learning models**. By leveraging **Non-Negative Matrix Factorization (NMF)** for topic modeling, we identify recurring patterns in customer complaints and categorize them into relevant financial service departments.

## Business Goal
Develop a **machine learning model** to classify customer complaints into predefined categories, allowing for quick issue resolution. The process involves:
- Identifying common topics in unstructured complaint data.
- Mapping complaints to five key product/service categories.
- Training a supervised model for future classification.

## Categories of Complaints
Customer complaints are classified into the following five categories:
1. **Credit card / Prepaid card**
2. **Bank account services**
3. **Theft/Dispute reporting**
4. **Mortgages/Loans**
5. **Others**

## Dataset
- The dataset contains **78,313 customer complaints** in **JSON format**.
- It has **22 features** describing various aspects of complaints.
- The dataset needs to be converted into a structured dataframe for further processing.

## Workflow
The project consists of the following major steps:
1. **Data Loading** - Read and process JSON data.
2. **Text Preprocessing** - Clean and prepare text data for analysis.
3. **Exploratory Data Analysis (EDA)** - Analyze patterns, word frequencies, and distributions.
4. **Feature Extraction** - Use TF-IDF for text vectorization.
5. **Topic Modeling** - Apply NMF to identify key complaint categories.
6. **Model Building (Supervised Learning)** - Train classifiers using labeled complaint data.
7. **Model Training & Evaluation** - Assess performance using accuracy, precision, recall, and F1-score.
8. **Model Inference** - Predict categories for new customer complaints.

## Machine Learning Models
After topic modeling, we create a **labeled dataset** and train supervised models for classification. We experiment with at least **three models** from the following:
- **Logistic Regression**
- **Naive Bayes**
- **Decision Tree**
- **Random Forest**

The best-performing model is selected based on evaluation metrics.

## Expected Outcome
- A trained **classification model** capable of categorizing new customer complaints.
- Improved efficiency in handling customer support tickets.
- Insights into recurring issues in financial services.

## Requirements
To run this project, you will need:
- **Python 3.x**
- **Libraries:** Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn
- **Jupyter Notebook** or any preferred Python IDE

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/customer-complaint-classification.git
   cd customer-complaint-classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook
   ```
4. Follow the steps in the notebook to train and evaluate models.

## Contribution
Feel free to contribute by:
- Enhancing text preprocessing techniques.
- Trying additional classification models.
- Improving evaluation and reporting.

## License
This project is licensed under the MIT License.

---
For any inquiries or feedback, contact m.kowatli97@gmail.com

