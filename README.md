# DSCI-310_GroupProject-Group-8_Online-Shopper-Intention
****

# Contributers/Authors
* Calvin Choi
* Nour Abdelfattah
* Sai Pusuluri
* Sana Shams

# Project Summary
Given the surge of online shopping, online retailers may get a lot of site traffic but what ultimately matters is whether or not users finalize their purchase. Marketing and User Experience teams are tasked with optimizing a site’s interface and content in order to improve customer retention and the site’s revenue. Given this, understanding customer browsing behaviour and web page features is crucial for not only improving the user’s experience, but also maximizing the retailer’s revenue.

This project aims to analyze various features of online shopper’s sessions on a site to predict whether the customer makes a purchase. We will use the dataset, [Online Shoppers Purchasing Intention](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset) dataset from the UCI Machine Learning Repository. 

# How to Run the Data Analysis
To replicate our analysis on your machine:
1. Clone this GitHub Repository on your local machine:
   * Click the green ``` Code <> ``` button and copy the URL.
   * On your local machine's terminal, navigate to the location where you would like this repository to reside in.
   * Run the command ``` git clone <URL> ``` in the terminal.
2. Creating the virtual environment
   * Navigate to the cloned repository on your machine.
   * Navigate to the ``` resources ``` folder from your terminal by running the command ``` cd resources ```
   * Run the command ``` conda env create --file ProjectMilestone1_venv.yaml ``` in the terminal. You may navigate out of the ``` resources ``` folder at this point. 
   * Activate the virtual environment by running the following command in the terminal: ``` conda activate ProjectMilestone1_env ```
3. Running the analysis
   * Open the repository folder on your IDE (may vary depending on IDE)
   * Navigate to the analysis file by opening the ``` project ``` folder, then open the file ``` Milestone1.ipynb ```
   * Make sure the kernel in your IDE is set to ProjectMilestone1_env.
4. Run the report from top to bottom in your IDE.
5. To deactivate the virtual environment, run the command ``` conda deactivate ``

# Running the Docker Container and Analysis

To run the project, you will have to run a docker container. To do so:
- Clone to project repository to your local computer 
- Navigate to the project directory DSCI-310_Group-Project_Group8 in a new terminal
- After doing so, type ```docker-compose up``` in your terminal
- This runs the container. You should find a set of URLs has been produced. 
- Launch the link that starts with http://127.0.0.1 in your browser
- Now that you are in jupyter, open a terminal and make sure you are in the project's root directory. 
- Use command ```make clean-all```  to reset the project
- Finally, type the ```make all``` command to run the analysis. 

# Dependencies
- ``` conda==23.11.0``` 
- ``` python=3.12``` 
- ``` pandas== 2.2.1``` 
- ``` jupyterlab==4.0.10``` 
- ``` numpy==1.26.4``` 
- ``` scikit-learn==1.4.0``` 
- ``` matplotlib==3.8.2``` 
- ```seaborn==0.13.2 ```
- ```click==8.1.7```

# License Information
This project is licensed under the terms of the MIT Licence, offered under the [MIT open source license](https://opensource.org/license/MIT). See the [LICENSE.md](https://github.com/DSCI-310-2024/DSCI_310_GroupProject_Group_8/blob/main/LICENSE.md) file for more information.

