# Learning Streamlit with Penguins 🐧 
In the Pythonic realm 🐍👑  of data and machine learning web application frameworks Streamlit has been acquiring quite a lot of popularity. In fact, Streamlit is designed  to be incredibly user-friendly. You can create interactive web apps with just a few lines of Python code. It abstracts away much of the complexity involved in web development, making it accessible even to those without a web development background. 

## How to use this repo 🛹
This repo will guide us step-by-step on building a 📊🧑🏽‍🔬DataScience Web Application 🧑🏽‍🔬📊 based on Streamlit. 

Feel free to explore the different branches.

### Environment 🌀 and Installation 👩🏽‍🔧👨🏽‍🔧
#### Prerequisite
+ Python 3.11.3 or above up to 3.11.6 (We will use [pyenv](https://github.com/pyenv/pyenv#simple-python-version-management-pyenv) for Python Version Management but feel free to use any other tool)
+ Virtual environment (We will use the module venv from python but you can use any other tool)


For __MacOs__/__Linux__ users
```bash
# Sets the local Python version to 3.11.3 using pyenv
pyenv local 3.11.3 
# Create a Virtual Environment named .streamlit_env using venv
python -m venv .streamlit_env
# Activate the Virtual Environment
source .streamlit_env/bin/activate
# Install Streamlit and Additional Libraries
pip install -r requirements.txt
```

For __Windows__ users with PowerShell CLI


```bash
# Sets the local Python version to 3.11.3 using pyenv
pyenv local 3.11.3 
# Create a Virtual Environment named .streamlit_env using venv
python -m venv .streamlit_env
# Activate the Virtual Environment
.streamlit_env\Scripts\Activate.ps1
# Install Streamlit and Additional Libraries
pip install -r requirements.txt
```

For __Windows__ users with GIT-BASH CLI


```bash
# Sets the local Python version to 3.11.3 using pyenv
pyenv local 3.11.3 
# Create a Virtual Environment named .streamlit_env using venv
python -m venv .streamlit_venv
# Activate the Virtual Environment
source .streamlit_venv/Scripts/activate
# Install Streamlit and Additional Libraries
pip install -r requirements.txt
```



#### 🧪 Test Streamlit Installation 👨🏽‍🔧👩🏽‍🔧
You can check if Streamlit is installed correctly and run a sample app with the following command:
```bash
streamlit hello
```
This should open a Streamlit web app in your default web browser. 

To run the application open the terminal and navigate to the folder containing the streamlit files eg. Home.py, pages/ etc.. and in the terminal type
`streamlit run Home.py`

## Further Readings 📚
The following is a list of other popular python web framework:
+ [Django](https://www.djangoproject.com)
+ [Dash](https://dash.plotly.com)
+ [Flask](https://flask.palletsprojects.com/en/3.0.x/)
+ [FastAPI](https://fastapi.tiangolo.com)
+ [Taipy](https://docs.taipy.io)
<br>
Both FastAPI and Flask are primarily focused on backend development for web applications.


## Aknowledgments 🙏🏼
I would like to thank [Dr. Paula González Avalos](https://github.com/pga99?tab=repositories) for having introduced me into the Penguins and Streamlit worlds. 


## License
[The MIT license](LICENSE)
