Breast Cancer Classification Using Machine Learning Algorithms

Version 1.0


-------------------------------------------------------------

README CONTENTS

1.0 Contact Information

1.1  Release Contents

1.2 Introduction

1.3 Requirements for Running the Project

1.4 Data Tables


-------------------------------------------------------------
1.0 Contact Information

Name:                       Email
Samuel Akinjole             soa52@drexel.edu

-------------------------------------------------------------

1.1  Release Contents

The contents of this project is listed below 
   readme.txt
   breast-cancer.csv
   Presentation-27
   27-Project Implementation.ipynb


-------------------------------------------------------------


1.2 Introduction

This project focuses classifying tumors into malignant (cancerous) or benign (non cancerous) through machine learning algorithms. The data used is from Kaggle titled "Breast Cancer Dataset". 

Subsequently, I used classification metrics to evaluate the performance of the models.

-------------------------------------------------------------
1.3 Requirements for Running the Project

This analysis was done in a Python 3 environment. Specifically, the Anaconda and Jupyter Notebook environment using the following packages:


pandas

numpy

sci-kit learn

matplotlib

seaborn



It is recommended to import the data into your environment from the

provided data file and begin analysis from there. For Python 3 we recommend

importing the CSV as a pandas dataframe. 



To run the notebook, execute the cells in sequence. The main steps include:

- Data Loading and Preprocessing: Ensure your dataset is correctly formatted and loaded.
- Exploratory Data Analysis and Data Wrangling: This is done to ensure high quality of the dataset and also get an understanding of the data.
- Model Definition: Define the models intended for use
- Training the Model: Train the model and tweak the hyper parameters to obtain the best results.
- Evaluating the Model: Use the provided metrics to measure the model’s performance on unseen test data.
- Model comparison: Run the provided plot visualization script



-------------------------------------------------------------

1.4 Data Tables

The dataset comprises of 32 columns and 569 instances
There are no missing or undefined values in the dataset.

The features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, basically describing the characteristics of the cell nuclei present in the image. The diagnosis column is the outcome with M = Malignant and B = Benign. There are 10 main features of the dataset, which are computed for each cell nucleus. These ten features in the dataset are:

- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry 
- fractal dimension ("coastline approximation" - 1)

	The mean, standard error (SE), and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 continuous features.
