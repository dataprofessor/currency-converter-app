# currency-converter-app

# Watch the tutorial video

[How to build a Currency Converter App | Streamlit #25](https://youtu.be/2gtlSLCTHH0)

<a href="https://youtu.be/2gtlSLCTHH0"><img src="http://img.youtube.com/vi/2gtlSLCTHH0/0.jpg" alt="How to build a Currency Converter App | Streamlit #25" title="How to build a Currency Converter App | Streamlit #25" width="400" /></a>

# Demo

Launch the web app:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/currency-converter-app/main/app.py)

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *currency-converter-app*
```
conda create -n currency-converter-app python=3.7.9
```
Secondly, we will login to the *currency-converter-app* environement
```
conda activate currency-converter-app
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/currency-converter-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/currency-converter-app/archive/main.zip

###  Launch the app

```
streamlit run app.py
```
