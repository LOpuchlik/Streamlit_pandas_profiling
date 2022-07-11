# Streamlit_pandas_profiling

Acknowledgements: I got inspired to write this app by an excellent youtuber: DataProfessor.

Streamlit pandas profiling app for basic exploration of preloaded or user-loaded datasets

There are two ways of exploring a dataset:
1) loading a custom dataset from a local file
2) choosing one of three example datasets: iris, titanic or boston housing

# How to run this program?

### Fork or copy the folder with the code to your local machine
* go to the target folder

### You need the following dependencies:
numpy==1.19.2 <br>
pandas==1.1.3 <br>
pandas-profiling==2.10.0 <br>
streamlit==0.71.0 <br>
streamlit-pandas-profiling==0.1.1

You can install them to a new environment from a file requirements.txt with a command:
#### $ pip3 install -r requirements.txt

### Update --> After trying to run this application after some time has passed I got into many errors due to the fact that some  of the dependencies got deprecated. This is how I fixed the problem after some googling:

#### $ pip3 install --upgrade protobuf==3.20.0
#### $ pip3 uninstall click
#### $ pip3 install click==8.0.4
#### $ pip3 uninstall flask
#### $ pip3 install Flask==2.1.0
#### $ pip3 install Jinja2==3.0.3

* run the programme by typing the following command in your terminal opened in the target directory:

#### $ streamlit run PandasProfilingApp.py

* the app should open in your browser
