# Iris-Flower-Classification
🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

This is a Week 3 project for the AI & ML course at NSP Nexus. The goal is to build a machine learning model using the K-Nearest Neighbors (KNN) algorithm to classify iris flowers into one of three species based on sepal and petal measurements.


---

📌 Objective

To build a basic classification model that predicts the species of an Iris flower (Setosa, Versicolor, Virginica) using the following features:

Sepal Length

Sepal Width

Petal Length

Petal Width



---

📊 Dataset

We use the Iris dataset provided by sklearn.datasets. It is a clean and well-known dataset for classification tasks.

Total samples: 150

Classes: 3 (Setosa, Versicolor, Virginica)

Features: 4 continuous numerical features



---

🔧 Tools & Libraries

Python

Jupyter Notebook / Google Colab

Libraries:

pandas

seaborn

matplotlib

sklearn (scikit-learn)




---

🧪 Steps Performed

1. Data Loading

Loaded the Iris dataset using sklearn.datasets.load_iris().



2. Data Preprocessing

Converted to a pandas DataFrame.

Added target labels as species names.



3. Data Exploration

Displayed first 5 rows.

Visualized data using Seaborn pairplot.



4. Train-Test Split

Used train_test_split() to split data into 70% training and 30% testing.



5. Model Training

Applied K-Nearest Neighbors with k=3.



6. Prediction & Evaluation

Evaluated the model using accuracy score.

Displayed confusion matrix using ConfusionMatrixDisplay.





---

🎯 Results

Accuracy: ~96% (may vary slightly depending on random split)

The model performs well in distinguishing between the 3 flower species.



---

📈 Visualizations

Pairplot of all feature combinations with species-colored data points.

Confusion Matrix to visualize prediction performance.



---

✅ Tips Followed (as per assignment)

✔ Used Seaborn for visualization

✔ Started with k=3 for KNN

✔ Code is clean and well-commented

✔ Notebook is GitHub-ready



---

📁 Project Structure

📂 Iris_KNN_Classification/
├── Iris_KNN_Classification_Fixed.ipynb
├── README.md


---

🚀 How to Run

1. Clone this repository or download the notebook.


2. Open in Jupyter Notebook or upload to Google Colab.


3. Run all cells to see data exploration, training, and evaluation.




---

📅 Submission Info

Name: Marten Jothi Victor

Email: mjv3140@gmail.com

Course: AI & ML (NSP Nexus – Week 3)

Deadline: Saturday, 11:59 PM

Submission: GitHub project link via Google Form



---

📬 Contact

For any issues or questions, feel free to raise an issue or contact me via email.
