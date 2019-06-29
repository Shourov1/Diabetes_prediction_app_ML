# Diabetes prediction application using Python

[![CircleCI](https://circleci.com/gh/Shourov1/Diabetes_prediction_app_ML.svg?style=svg)](https://circleci.com/gh/Shourov1/Diabetes_prediction_app_ML) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This application is made using [sklearn](https://en.wikipedia.org/wiki/Scikit-learn) Machine Learning libraries and [pyqt5](https://pypi.org/project/PyQt5/) for its graphical UI. 

Support Vector Machine classifies input data with 80% accuracy. [PIMA Indians diabetes dataset](https://archive.ics.uci.edu/ml/datasets/diabetes) from the UCI archive is used to train the model.

<img src="./screenshots/Screenshot.png" width="250">

## How to start

Firstly install all dependencies via the following commands.

```bash
pip3 install -r requirements.txt
```

Now train the application in machine as

```bash
python3 diabetes.py
```

Finally run the application:

```bash
python3 gui.py
```
Now insert all the requires details to see the result.

## Built With
* [Python 3.7](https://www.python.org/downloads/).
* [PyQt5](https://pypi.org/project/PyQt5/) - for the GUI.

## Author

* **Md Shariful Alam** - [Shariful](https://github.com/Shourov1)

## Acknowledgments

*[UCI archive](https://archive.ics.uci.edu/ml/index.php) - for providing the datasets.
