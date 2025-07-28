# Table of Contents
1. [Project Motivation](test)
2. [Project Design](design)
3. [Technology / Packages Used](tech)
4. [Functional Features](features)
5. [Installation](install)
6. [File Descriptions](files)
7. [Licensing, Authors & Acknowledgements](licAutAck) 

## 1. Project Motivation
There are two important aspect of any data science project. First is the problem statement and its solution, and second is Its Story and outcomes. This project is also address these two steps. First part is fully managed and maintained in this github repository. For second part, a medium blog post is used to tell the story of the project. 
## 2. Project Design
Project is built using Jupitor Notebook and fully based on Python packages. It follows **CRISP-DM** process guidance for managing the lifecycle of the project. 
## 3. Technology / Packages Used
Following python packages are used to build this data science project:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## 4. Functional Features
The project has following functional objectives/features: 
- It uses the publick data set from StackOverflow site named "Tech Careers - StackOverflow Developer Survey". [developer survey homepage](https://www.google.com/url?q=https%3A%2F%2Fsurvey.stackoverflow.co%2F)
- From the site 2024 data is used for building the prediction model
- Dataset is used to build a prediction model for Developers based on key features from the dataset.
- As a first step, project performs exploratory analysis on the data, do cleanse the data for use in the prediction model, including feature selection / reduction to important features.
- In Second Step, project trains the model using the data 
- In the final step project Validates its performance using various metrics.

## 5. Installation 
- Create a folder DSBlog and change working directory to that
- Create a virtual environment in side the directory (where you will be running the notebook.)
- Activate the virtual environment
- Install jupyter using command ' pip3 install jupyter' inside your activated python virtual envirlonment
- Copy the Notebook file in this folder 
- Extract the data file by unzipping it and move it to the subfolder "data" where 
- Inside notebook, uncomment the first shell ("Install Packages Section") to install all required packages.
- Your project code is ready from inside the notebook.

## 6. Files Descriptions
Listed below are all the files and their respective purpose and description which are part of this project's repository
- readme file (README.md)
- jupitor notebook
- Data File (Zip) -> to be extracted to data subfolder. 

## 7. Licensing, Authors & Acknowledgement
#### Licensing:
There is no licencing terms associated with this project. This repository can be reference, reproduced, reused as the readers find usefule for them. No obligation from the author and owner of this project. 
#### Authors:
Prakash Chandra Binwal is the sole owner and author of this project. 
#### Acknowledgements 
While working on this project and run-0up to it, there are multiple forums, people, roles that has their share in enabling me achieve this. Some are listed below ... 
- Udacity instructors
- Other academic and Training Insttructors along the way
- Public Communities and parent documentations of various packages used in building this project
- On job experience and learnings 
