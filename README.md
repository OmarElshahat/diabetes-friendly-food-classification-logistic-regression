🥗 Diabetes Food Classification with Logistic Regression
📌 Overview

This project is my first supervised machine learning classification model. The goal is to predict how often different food items should be consumed:

More Often

In Moderation

Less Often

The dataset contains nutritional information about food items (calories, fats, sugars, proteins, vitamins, etc.). While the dataset is general, this model has potential applications in helping people with diabetes make better food choices by identifying which foods may be more suitable for frequent consumption.

🎯 Objectives

Learn and apply supervised machine learning (classification).

Train a Logistic Regression model to classify food items.

Evaluate performance using accuracy, precision, recall, and F1-score.

Explore applications for health and diabetes nutrition guidance.

📊 Dataset

Source: IBM Skills Network food_items.csv

Size: ~13,000 rows × 18 columns

Features: Calories, Total Fat, Sugars, Protein, Sodium, Vitamins, etc.

Target Classes: "More Often", "In Moderation", "Less Often"

⚙️ Methodology

Data Preprocessing

Scaling numeric features with MinMaxScaler.

Encoding categorical values with LabelEncoder.

Model Training

Algorithm: Logistic Regression (Scikit-Learn).

Train-test split: 80/20.

Evaluation

Metrics: Accuracy, Precision, Recall, F1-score.

Visualization: Confusion Matrix (heatmap).

📈 Results

Overall Accuracy: 80.9%

Per-Class Performance:

Class	Precision	Recall	F1-score
In Moderation	0.79	0.85	0.82
Less Often	0.84	0.74	0.79
More Often	0.83	0.87	0.85

The model performs best on “More Often” foods with high recall (87%).

“In Moderation” foods are also classified well, balancing precision and recall.

“Less Often” foods show slightly lower recall (74%), suggesting room for improvement with more balanced data.

(Insert confusion matrix screenshot here)

🧠 Applications for Diabetes

Identifying foods safe to eat more often (low sugar, high fiber, nutrient-rich).

Flagging foods that should be eaten less often (high sugar, high fat, processed).

Can serve as a starting point for AI-driven nutrition guidance systems.

⚠️ Note: This model is for educational purposes only and should not replace medical or dietary advice.

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/diabetes-food-classification-logistic-regression.git
cd diabetes-food-classification-logistic-regression


Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook and run:

jupyter notebook Untitled2.ipynb

🔮 Next Steps

Experiment with Decision Trees, Random Forests, and Neural Networks.

Balance the dataset to improve performance on underrepresented classes.

Extend the project to provide personalized food recommendations.

🙌 Acknowledgments

Dataset: IBM Skills Network

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

📬 Connect

I’m sharing this project as part of my data science learning journey.
👉 Let’s connect on LinkedIn
 and discuss more about machine learning and health-tech applications!