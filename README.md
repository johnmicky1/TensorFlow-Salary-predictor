🐍 TensorFlow Project Setup & Organization Guide
This guide details the steps to set up the environment and run the TensorFlow-based Salary Predictor model.
📁 Project Structure
Your project folder, Salary_Predictor/, should contain the following structure:  
Salary_Predictor/  
├── 📊 salary_data_small.csv  
├── 🐍 salary_predictor_actual_tf.py  
├── 📁 tf_env/                 # Python Virtual Environment (Created in Step 2)  
└── 📄 README.md
🔧 Step 1: Create Project Folder
Use the command line to create and navigate into your project directory.  
# Create project folder on Desktop  
mkdir "Salary_Predictor"
# Navigate into the new folder  
cd "Salary_Predictor"
🐍 Step 2: Set Up Virtual Environment
It's best practice to use a virtual environment (tf_env) to isolate your project's dependencies.  
# Create virtual environment (using Python 3.13)  
py -3.13 -m venv tf_env
# Activate virtual environment (for Windows Command Prompt/PowerShell)  
tf_env\Scripts\activate
📦 Step 3: Install Required Packages
With the environment activated, install all necessary libraries, including TensorFlow, Pandas, and Scikit-learn.  
# Install all packages in one command  
pip install tensorflow pandas numpy matplotlib scikit-learn joblib jupyterlab
# Verify TensorFlow installation  
python -c "import tensorflow as tf; print('TensorFlow version:', tf.__version__)"
