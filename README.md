# Agricultural-Land-Classification

Introduction
Determining how land is used is a huge problem today. After all, its improper and illegal use can lead to both economic and natural disasters. One of the ways to assess the use is the analysis of aerial and satellite images of the earth's surface. A big problem is to build a mathematical model that can determine the type of land use based on colors. If you have ready-made photos and masks of land use, you can use the methods of artificial intelligence and big data to build a model-classifier.

In this lab, we will learn how to upload photos, transform pixels and colors into a data set. Then we will learn how to build a classifier and predict land use masks based on it.

Materials and methods
In this lab, we will learn the basic methods of images transformation classification. The laboratory consists of four stages:

Download and visualization of images
DataSet creation
Classification model creation
Create your own mask of land use
The statistical data was obtained from https://www.kaggle.com/humansintheloop/semantic-segmentation-of-aerial-imagery under CC0: Public Domain license.

Prerequisites
Python - basic level
numpy - middle level
SeaBorn - basic level
Matplotlib - basic level
scikit-learn - middle level
pandas - basic level
Objectives
After completing this lab, you will be able to:

Download and transform images.
Create a DataSet of the colors of images.
Build a classification model.
Build land use masks based on a classifier.
Download and visualization of images
Install the required libraries
We need to install additional libraries and upgrade existing ones in the lab.


conda install matplotlib >= 3.4

PackagesNotFoundError: The following packages are not available from current channels:

  - 3.4

Current channels:

  - https://repo.anaconda.com/pkgs/main/linux-64
  - https://repo.anaconda.com/pkgs/main/noarch
  - https://repo.anaconda.com/pkgs/r/linux-64
  - https://repo.anaconda.com/pkgs/r/noarch

To search for alternate channels that may provide the conda package you're
looking for, navigate to

    https://anaconda.org

and use the search bar at the top of the page.



Note: you may need to restart the kernel to use updated packages.
