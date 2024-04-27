# K-Means Algorithm from Scratch
## Project Overview
This project recreates the K-Means algorithm from scratch using distance concepts like L-2 Norm(Euclidean Distance) and Geometric Mean. It then compares it to the K-Means implementation from scikit-learn and labels from the original dataset. The dataset used is the Iris flower dataset containing sepal length, width and petal length, width for 3 different types of irises' (Setosa, Versicolour, and Virginica) stored in a 150x4. Each type of irises has 50 instances in the dataset. The labels are removed for PCA since the goal is assinging a cluster for each datapoint in the dataset.

Recreating the K-Means algorithm provides insights into

* Underlying concepts of the algorithm
* Strenghts and Drawbacks of the algorithm
* Customization potential 

For a detailed explanation on the theory used for this computation, check out the accompanying [article on medium](https://medium.com/@ayoakinkugbe/build-k-means-from-scratch-341285b8d481)

### Code
You can find the code for this project [here](https://github.com/ayoakin/K_Means_From_Scratch/blob/main/Build_K_Means_From_Scratch.ipynb).

File overview:

* `Build_K_Means_From_Scratch.ipynb` - the full code from this project


## Environment Setup

### Installation
To follow this project, please install the following locally:

* Python 3.8+
* Python packages
  * pandas
  * numpy
  * scikit-learn
  * Matplotlib

### Data

The data used for this implementation is the salary data originally on [Kaggle](https://www.kaggle.com/datasets/uciml/iris).

You can download the file we'll use in this project here:

* [IRIS.csv](https://github.com/ayoakin/K_Means_From_Scratch/blob/main/IRIS.csv) - the Iris dataset used in this project.
