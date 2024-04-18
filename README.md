# Big AgriSenze Jupyter Notebook Project


## Installing dependencies
Python version: >= 3.12.2
1. Install latest anaconda or miniconda for a conda environment
2. Clone the project from git repository 
3. Locate the cloned project directory/folder
4. Re-create the virtual environment and activate your virtual environment
	> conda create --name env --file requirements.txt
	> conda activate <full path to your env file>
	OR
	> conda create --name <your_env_name>
	> conda activate <full path to your_env_name>  
	Modify the requirements.txt file to have package name = version number by the removing the additional ='******' at the end for all packages
	> pip install requirements.txt

5. Open Jupyter Notebook by running
    > jupyter notebook
6. Install additional necessary packages from Jupyter Notebook
	> conda install <packag_name>  
	OR 
	> !pip install <packag_name


## Update Virtual Environment Requirements file
   > conda list --export > requirements.txt
