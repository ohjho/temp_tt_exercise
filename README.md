# Hello World!
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
![tested-on-osx](https://img.shields.io/badge/Tested%20on-OSX-lightgrey.svg)

A simple Supervised Machine Learning Model for Binary Classification! See the [Jupyter Notebook](exercise.ipynb).

## To Run this on your machine
1. Clone this repo:
```
$ git clone https://github.com/ohjho/temp_tt_exercise.git
$ cd temp_tt_exercise
```
2. install the requirements. **Highly recommend** doing this inside a [virtualenv][url_virtualenv] and avoid [dependency hell](https://medium.com/knerd/the-nine-circles-of-python-dependency-hell-481d53e3e025).  
```
$ mkvirtualenv --python=`which python3` NameOfYourEnv
$ workon NameOfYourEnv
(NameOfYourEnv) $ pip install -r requirements.txt
```
3. Start up the Jupyter Notebook:
```
(NameOfYourEnv) $ jupyter notebook
```

[url_virtualenv]: https://virtualenvwrapper.readthedocs.io/en/latest/
