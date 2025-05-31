
🌸 Iris Flower Classification 🌸

A beginner-friendly machine learning project that classifies iris flowers into three species — Setosa, Versicolor, or Virginica — based on their petal and sepal measurements.


---

📊 Project Overview

Type: Supervised Learning – Classification

Algorithm Used: Random Forest

Dataset: sklearn.datasets.load_iris() (built-in)

Tools: Python, Scikit-learn, Pandas, Matplotlib, Seaborn

Accuracy: ~95%+



---

📁 Features

Feature	Description

Sepal Length	in cm
Sepal Width	in cm
Petal Length	in cm
Petal Width	in cm
Target	Iris Species (0, 1, 2)



---

🧠 Steps Covered

1. Importing the Iris dataset


2. DataFrame creation using Pandas


3. Exploratory Data Analysis using Seaborn


4. Splitting data into training & testing sets


5. Model training with RandomForestClassifier


6. Accuracy score calculation


7. Predicting species from new input




---

📌 Sample Prediction

sample = [[5.1, 3.5, 1.4, 0.2]]
predicted = model.predict(sample)
print("Predicted species:", iris.target_names[predicted][0])


---

🎯 Output

Accuracy: 0.977...
Predicted species: setosa


---

📂 Project Setup 

Run this project on:

Google Colab


---

🙋‍♀️ Made By

Kushi A.
B.E. in Artificial Intelligence & Data Science
East West Institute of Technology
