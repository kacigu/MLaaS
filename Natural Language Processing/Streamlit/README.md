## How to Reproduce this Web Application

To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *tfg-nlp*
```
conda create -n tfg-nlp python=3.7.9
```
Secondly, we will login to the *tfg-nlp* environement
```
conda activate tfg-nlp
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://github.com/TechForGoodInc/MLaaS/blob/main/Natural%20Language%20Processing/Streamlit/requirements.txt
```

Pip install libraries
```
pip install -r requirements.txt
```

### Download and unzip this directory

Download [this directory](https://github.com/TechForGoodInc/MLaaS/tree/main/Natural%20Language%20Processing/Streamlit) and unzip as your working directory.

###  Launch the app

```
streamlit run app.py
```

** Please note, the requirements.txt file is not fully customized to this particular application. Will be updated soon accordingly.
