# Bigotry Detection

This repository contains the work of my first data science project. The project applies data science techinques to annotated Reddit comment data and emotion sensor features, culminating in a successful bigotry detection model. 

## Notebooks 
Folder contains all code.
 - [Data Wrangling](https://github.com/mstahli6/Capstone_Two_MS_SB_Repo/blob/main/Notebooks/Data%20Wrangling.ipynb)
 - [Exploratory Data Anaysis](https://github.com/mstahli6/Capstone_Two_MS_SB_Repo/blob/main/Notebooks/Exploratory%20Data%20Analysis.ipynb)
 - [Pre-Processing](https://github.com/mstahli6/Capstone_Two_MS_SB_Repo/blob/main/Notebooks/Pre-processing.ipynb)
 - [Modelling](https://github.com/mstahli6/Capstone_Two_MS_SB_Repo/blob/main/Notebooks/Modelling.ipynb)

## Reports
 -  [Bigotry Detection Report](https://github.com/mstahli6/Capstone_Two_MS_SB_Repo/blob/main/Bigotry%20Detection%20Report.pdf)
Full report on entire process.
 - [Bigotry Detection Presentation PDF](https://github.com/mstahli6/Capstone_Two_MS_SB_Repo/blob/main/Bigotry%20Detection%20Presentation%20PDF.pdf)
MS PowerPoint presentation. 

### Emotion Sensor Data
[Csv dataset](https://github.com/mstahli6/Capstone_Two_MS_SB_Repo/blob/main/Emotion%20Sensor%20Data/Andbrain_DataSet.csv) of 1004 words scored on seven emotions. 

### Business Case:
This project will use labeled Reddit data to create a detection model that flags comments that likely contain bigotry. The application is for businesses willing to build a reviewing team to go through comments flagged by the detection model, à la human-in-the-loop (HITL). This has the obvious drawback of requiring more resources in terms of human-worked-hours, but avoids the potential of filtering out comments that were never an issue in the first place.  We assume that the business has the capacity to review up to 10% of comment traffic on their platform.
