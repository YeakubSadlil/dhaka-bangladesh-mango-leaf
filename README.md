# Omdena Bangladesh Chapter: Real-Time Automated Mango Leaf Disease Detection in Bangladesh Using CNNs

## Table of Contents
* [Introduction](#Introduction)
* [Problem Statement](#Problem-Statement)
* [Project Goals](#Project-Goals)
* [DAX Formulas Used in Measures](#DAX-Formulas-Used-in-Measures)
* [Bug / Feature Request](#Bug--Feature-Request)
* [Authors](#Authors)

## Introduction
* Agriculture plays a vital role in Bangladesh’s economy, contributing 11.5% to the GDP. Fruits comprise 10% of national income.
* Bangladesh ranks 7th in mango production globally and it is known as the king of fruits.
* Bangladesh’s annual mango production is around 1.2 million metric tons from over 100,000 acres of land.
* However, despite its potential, mango production in the country faces challenges, including pest attacks and diseases caused by bacteria, fungi, viruses, and insects.
* These diseases lead to a substantial annual yield loss of around 30%, impacting farmers’ livelihoods and national production.

## Problem Statement
* Bacterial and fungal diseases are major constraints for mango production, causing around 30% yield loss annually.
* The absence of real-time, automated systems for early detection and classification of mango leaf diseases hampers efforts to mitigate crop losses.
* Currently, farmers face delayed diagnoses which reduces productivity and causes financial losses.
* This project aims to address this problem by developing a cutting-edge computer vision-based model that provides instant in-field detection and classification of mango leaf diseases, empowering farmers with timely information to reduce losses and enhance their income

## Project Goals
* The project goals are:
    * Collect a comprehensive dataset of mango leaf images encompassing multiple bacterial and fungal diseases, ensuring representation across various regions.
    * Train and optimize Convolutional Neural Network (CNN) models to accurately detect and classify mango leaf diseases using the collected dataset.
    * Develop an intuitive user interface with trained models for real-time mango disease screening by farmers.

## Contribution Guidelines
- Have a Look at the [project structure](#project-structure) and [folder overview](#folder-overview) below to understand where to store/upload your contribution
- If you're creating a task, Go to the task folder and create a new folder with the below naming convention and add a README.md with task details and goals to help other contributors understand
    - Task Folder Naming Convention : _task-n-taskname.(n is the task number)_  ex: task-1-data-analysis, task-2-model-deployment etc.
    - Create a README.md with a table containing information table about all contributions for the task.
- If you're contributing for a task, please make sure to store in relavant location and update the README.md information table with your contribution details.
- Make sure your File names(jupyter notebooks, python files, data sheet file names etc) has proper naming to help others in easily identifing them.
- Please restrict yourself from creating unnessesary folders other than in 'tasks' folder (as above mentioned naming convention) to avoid confusion. 

## Project Structure

    ├── LICENSE
    ├── README.md          <- The top-level README for developers/collaborators using this project.
    ├── original           <- Original Source Code of the challenge hosted by omdena. Can be used as a reference code for the current project goal.
    │ 
    │
    ├── reports            <- Folder containing the final reports/results of this project
    │   └── README.md      <- Details about final reports and analysis
    │ 
    │   
    ├── src                <- Source code folder for this project
        │
        ├── data           <- Datasets used and collected for this project
        │   
        ├── docs           <- Folder for Task documentations, Meeting Presentations and task Workflow Documents and Diagrams.
        │
        ├── references     <- Data dictionaries, manuals, and all other explanatory references used 
        │
        ├── tasks          <- Master folder for all individual task folders
        │
        ├── visualizations <- Code and Visualization dashboards generated for the project
        │
        └── results        <- Folder to store Final analysis and modelling results and code.
--------

## Folder Overview

- Original          - Folder Containing old/completed Omdena challenge code.
- Reports           - Folder to store all Final Reports of this project
- Data              - Folder to Store all the data collected and used for this project 
- Docs              - Folder for Task documentations, Meeting Presentations and task Workflow Documents and Diagrams.
- References        - Folder to store any referneced code/research papers and other useful documents used for this project
- Tasks             - Master folder for all tasks
  - All Task Folder names should follow specific naming convention
  - All Task folder names should be in chronologial order (from 1 to n)
  - All Task folders should have a README.md file with task Details and task goals along with an info table containing all code/notebook files with their links and information
  - Update the [task-table](./src/tasks/README.md#task-table) whenever a task is created and explain the purpose and goals of the task to others.
- Visualization     - Folder to store dashboards, analysis and visualization reports
- Results           - Folder to store final analysis modelling results for the project.


