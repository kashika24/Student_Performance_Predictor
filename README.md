# Student_Performance_Predictor

### steps to run the project
#Cloning the repository: git clone https://github.com/kashika24/Student_Performance_Predictor.git
#Setting up the environment: creating a virtual environment-
   # You can create a virtual environment using venv (which is included with Python 3.3+) or conda.

        #Using venv:
        
        #Navigate to the project directory in your terminal.
        #Create the virtual environment:
        python -m venv venv
        #Use code with caution
        #(This creates a directory named `venv` containing the virtual environment)
        #Activate the virtual environment:
        #On Windows:
        .\venv\Scripts\activate
        #Use code with caution
        #*   On macOS and Linux:
        source venv/bin/activate
        #Use code with caution
        #Using conda:
        
        #If you have Anaconda or Miniconda installed, navigate to the project directory.
        #Create the virtual environment:
        conda create -n student_performance python=3.x
        #Use code with caution
        #(Replace `3.x` with the Python version you used for the project, e.g., `3.9`)
        #Activate the virtual environment:
        conda activate student_performance
        #Use code with caution
        #Once the virtual environment is activated, you can install the project dependencies.
        
#Installing dependencies: pip install -r requirements.txt
#Running the notebook: open the .ipynb file in Jupyter Notebook or Google Colab.
#Brief project description: 
    This project focuses on building a machine learning model to predict student academic performance. Using the "student-mat.csv" dataset, the project explores 
    various factors influencing student outcomes, including grades, demographics, and lifestyle choices. The goal is to develop a model that can predict final 
    grades (G3) and classify students based on their pass/fail status, providing valuable insights for educators and students to identify areas for improvement and 
    intervention.

