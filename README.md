# Python Iris Classifier
Rodriguez Larreta, Martinez Casas & Vallejo Garnica

Description
The Python Iris Classifier is a project that aims to classify iris flowers into different species based on their sepal and petal measurements. The project utilizes a logistic regression model to make predictions on new iris samples.

Motivation
The motivation behind this project is to showcase the application of machine learning algorithms in solving classification problems. By building a classifier for iris flowers, it demonstrates how data analysis and modeling techniques can be used to identify and classify different species based on their characteristics.

Features
- Load and analyze the Iris dataset
- Check for missing values in the dataset
- Assess the balance of the dataset
- Visualize the correlation between features
- Calculate the mean values for each species
- Create a pairplot to visualize relationships between features
- Split the dataset into training and testing sets
- Standardize the input features
- Train a logistic regression model
- Evaluate the model's performance using accuracy score, precision, recall, F1 score, and confusion matrix
- Provide a graphical representation of the ROC curve
- Build a user-friendly GUI for predicting iris species based on user input

Installation
To run the Python Iris Classifier project, follow these steps:

1. Clone the project repository from GitHub.
2. Install the required libraries by running the following command: `pip install -r requirements.txt`.
3. Make sure you have Python installed on your machine.
4. Run the Python script `Iris_Python.ipynb` to launch the GUI.

Usage
1. Launch the GUI by running the `Iris_Python.ipynb` script.
2. Enter the sepal and petal measurements of an iris flower
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
4. Click the "Predict Iris" button to classify the iris species.
5. The predicted species will be displayed in the GUI, along with an image representing the predicted species.

Credits
The Python Iris Classifier project was developed by Victoria Vallejo, Paloma Rodriguez Larreta and Carmela Martinez Casas. We would like to acknowledge the following resources:

- The Iris dataset used in this project: https://archive.ics.uci.edu/dataset/53/iris
- [Scikit-learn](https://scikit-learn.org/) library for machine learning algorithms
- [Pandas](https://pandas.pydata.org/) library for data manipulation and analysis
- [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) libraries for data visualization
- [Tkinter](https://docs.python.org/3/library/tkinter.html) library for creating the GUI
- [Pillow](https://python-pillow.org/) library for image handling

