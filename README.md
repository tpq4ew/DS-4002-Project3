# DS-4002-Project3
This goal of this project is to develop a ResNet-50 image classification model that accurately classifies avocado ripeness into predefined stages. By training on a large dataset of labeled avocado images, the model will assess ripeness stages to help reduce waste and support applications in retail and agriculture. The model’s success will be evaluated using accuracy, precision, recall, and F1 score metrics, with statistical significance confirmed through a one-sample t-test. The Centro de Biotecnologia e Quimica Fina developed the dataset and is available through the journal Mendeley Data. The dataset contains 14,710 labeled images of Hass avocados, resized to 800 x 800 pixels and saved in .jpg format. The data was sourced from 478 avocados acquired 3 days post-harvest, and the samples were divided into 3 storage conditions: 10 C with 85% relative humidity, 20 C with 85% relative humidity, and ambient conditions. Daily pictures captured the ripening process across 5 stages to track shelf life: underripe, breaking, ripe (first stage), ripe (second stage), and overripe. An accompanying Excel sheet detailed each image’s file name, time stamp, group, sample, day of the experiment, and ripening index classification.

Software and Platforms: All code for this project was developed and executed in Google Colab, ensuring ease of collaboration and reproducibility. The project makes use of several key Python packages: pandas for data manipulation and cleaning, matplotlib for visualizations, Ultralytics YOLO for real-time object detection and image segmentation, and shutil for high-level organization for files. Additionally,numpy is employed for numerical operations throughout the analysis. All of these package downloads are included in the code to make sure that anyone who runs the code can reproduce the results. The program was run across different computers but the online nature of the coding process prevented any problems with the type of computer platform that we individually used.

File Directory:

README.md : This document contains general information about the project and files included in this Repo

LICENSE.md : Licensing and copyright reproducibility information

DATA FOLDER This folder contains all data files, both raw and cleaned, that are used in the project.

These datasets were the final datasets that we used to conduct analysis:
north_average_admission_rate_by_year.csv
north_average_tuition_by_year.csv
south_average_admission_rate_by_year.csv
south_average_tuition_by_year.csv

SCRIPTS FOLDER This folder contains any code used in the project:
Visualizations_and_Exploration.ipynb: This is the cleaning code that we used to reformat that raw data set downloaded from Mendeley Data. This code also generates the visualizations that we used in our original data understanding phase. 

Project 3 Analysis.ipynb : This runs the analysis and the network for our project.

OUTPUT FOLDER This folder contains any visual outputs used for preanalysis and understanding of the data set. Files in this folder are named according to their relevance. 

Project 3 Presentation: This file includes the slides that will be presented in class.
