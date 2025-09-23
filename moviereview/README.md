🎬 Movie Review Sentiment Analysis

This project analyzes movie reviews and predicts their sentiment using machine learning models. It is part of my Codsoft Internship tasks.

📂 Project Structure
├── moviereview.ipynb   # Jupyter Notebook with the full analysis & model
├── README.md           # Project documentation

⚙️ Requirements

Make sure you have Python 3.8+ installed. Install the required dependencies with:

pip install -r requirements.txt


Typical requirements:

pandas

numpy

scikit-learn

matplotlib

seaborn

jupyter

🚀 How to Run

Clone the repository:

git clone https://github.com/Shadinbm/Codsoft-Internship.git
cd Codsoft-Internship


Open the Jupyter Notebook:

jupyter notebook moviereview.ipynb


Run the cells step by step to see data preprocessing, model training, and evaluation results.

📊 Models Used

Linear Regression

Random Forest

Support Vector Regression (SVR)

Decision Tree

🏆 Results

The models were evaluated using MAE, MSE, and R² score.
Best performance was achieved with Random Forest, showing better predictive accuracy compared to other regressors.

✨ Findings

Income-related and categorical features like director names played a role in predicting outcomes.

Encoding techniques (Label Encoding, OneHotEncoding) were used for categorical variables.

Model comparison helped identify the most reliable regressor for the dataset.

📌 Future Improvements

Hyperparameter tuning for better accuracy.

Try deep learning models (e.g., LSTM for textual reviews).
