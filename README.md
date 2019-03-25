# lsml19
Practical sessions for the [2019 Large Scale Machine Learning course at MINES ParisTech](http://cazencott.info/index.php/pages/LSML-19-Large-Scale-Machine-Learning). 

## 2019-03-25  Introduction to Machine Learning with Python

This repository contains Jupyter notebooks for the first  afternoon of practical sessions of the LSML 2019 course.

To run the notebooks, you need to start Jupyter by typing

  ```jupyter notebook```

in a terminal. This will open a file navigator in your web browser. Navigate to this repository. You can then open any notebook by clicking on it.

**If you are working on a MINES ParisTech machine, you need to first add the path to jupyter to your PATH environement variable:**
 ```bash
 export PATH=/opt/anaconda2/bin:$PATH
 ```

If you are already familiar with Python and numerical Python (numpy) as well as matplotlib, you can start with Notebook 3. We recommend, however, doing the small problems in Notebooks 1 and 2 to familiarize yourselves with Jupyter and refresh your knowledge of these tools.

The focus of our first afternoon of practicals is going to be Notebooks 3 and 4, which introduce data manipulation and machine learning with scikit-learn. If you still have time, you can get started on Notebook 5.

## 2019-03-26 Feature engineering with Python

We have so far assumed that our data is represented by a well-behaved matrix X with n rows/samples and p columns, each corresponding to a feature. An important part of data science, however, is to transform raw data in such features.

Start with Notebook 5 (from the previous day) and move on to Notebook 6, where you'll explore data pre-processing in more details.

## 2019-03-26 Convolutional Neural Networks

If you have never trained a ConvNet before (in particular, if you did not take the "Apprentissage Artificiel" course by Fabien Moutarde), start with LSML19_CNN_Introduction.ipynb, available [on CoLab](https://colab.research.google.com/drive/1QNKEppw6bcZbpllFjBHppO2gnRJ6dYTZ). As a backup, the lab is also available at http://perso.mines-paristech.fr/fabien.moutarde/ES_MachineLearning/Practical_deepLearning-convNets/practical_deepLearning-ConvNets.html.

Then you can move on to transfer learning with deep networks LSML19_Transfer_Learning.ipynb, available [on CoLab](https://colab.research.google.com/drive/1LXz9Sior_X4X8Xe8DfzpgLPQ4pK2sk3u). As a backup, the lab is also available at http://perso.mines-paristech.fr/fabien.moutarde/ES_LSML/TP_TransferLearning-ConvNet/TP_TransferLearning-ConvNets.html.

## 2019-03-27 Stochastic Gradient Descent

A large part of machine learning rests on convex optimization and gradient descent techniques. How does one perform gradient descent with large data? This is what you'll explore in Notebook 7.
