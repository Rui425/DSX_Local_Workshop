# DSX Local Workshop
In this workshop you will learn how to develop and deploy applications in DSX Local. The workshop has been divided into several stand-alone parts for those who are interested in a certain development tool or a certain deployment task. 

## About this repository
This repository contains several lab subfolders. Some labs include notebooks and data, while others have additional instructions that are located in the *Lab Instructions* folder. 

## Prerequisites
1. Knowledge of analytics. These labs do not teach you the basics of analytics or how to implement analytics in R, Python and SPSS. The purpose of this workshop is to provide hands-on experience with analytics tools and deployment functions in DSX. 
2. To run this workshop you need an instance of DSX Local. 
3. Download and unzip this [this repository](https://codeload.github.com/elenalowery/DSX_Local_Workshop/zip/master). Unzip the repository only, not files in subfolders. 

### Setting up lab projects in DSX Local
1. In the **DSX_Local_Projects** folder, locate the **DSX_Local_Workshop.zip** file and rename it to give it a unique name.  For example, add your initials.    *Note: Project names in DSX Local cluster must be unique. When we create a project "from file", the project name is inherited from the file name*.
2. Log in to DSX Local.
3. Select "Create New Project" and select "From File".
4. Browse to the .zip file and click **Create**.
![ProjectFromFile](/img/CreateProjectFromFile.JPG?raw=true).

### Lab 1: Build, Save and Test SparkML Models (Jupyter/Python)
1. Open the project you just created. 
2. Navigate to **Assets** view and open **TelcoChurn_SparkML** *Jupyter* notebook. This notebook has been implemented for the Python 2.7 runtime. You can verify the runtime by running the first cell in the notebook. 
3. Follow instructions in the notebook.

### Lab 2: Build, Save and Test Scikit-Learn Models (Jupyter/Python)
1. Open the project you just created. 
2. Navigate to **Assets** view and open **CreditCardDefault_SkLearn** notebook. If you want to stay with the telco churn example, you can work through the **TelcoChurn_SkLearn** notebook. 
3. Follow instructions in the notebook.

### Lab 3: Build, Save and Test SparkML models (Zeppelin/Python)
1. Open the project you just created. 
2. Navigate to **Assets** view and open **TelcoChurn_Zeppelin** notebook.
3. Follow instructions in the notebook.

### Lab 4: SPSS Modeler in DSX
1. Follow instructions in the SPSS_Modeler_in_DSX.pdf document in the Lab Instructions folder of the unzipped repository

### Lab 5: Batch deployment of analytics (Batch Scoring in DSX)
1. Follow instructions in the **DSX_Batch_Scoring.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

### Lab 6: Model Evaluation
1. Follow instructions in the **DSX_Evaluation_in_DSX.pdf** document in the **Lab Instructions** folder of the unzipped repository. 


