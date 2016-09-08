# B-CADMCI
Computer-Aided Diagnosis Tool for Mild Cognitive Impairment based on Keras Sequential Model

## Motivation
B-CADMCI is built on top of [keras](https://github.com/fchollet/keras) and [scikit-learn](https://github.com/scikit-learn/scikit-learn). It was developed to aid in the diagnosis of Mild Cognitive Impairment by analyzing the scores of different cognitive tests:
- Mini–Mental State Examination (MMSE)
- Montreal Cognitive Assessment (MoCA)
- Clinical Dementia Rating (CDR)
- Global Deterioration Scale (GDS)

B-CADMCI contains artificial neural networks trained with different databases like [ADNI](http://adni.loni.usc.edu/) to predict the level of patient's cognitive impairment and guide the clinicians in the diagnosis of the disease.

## Dependencies
B-CADMCI is tested to work under Python 3.4
The required dependencies to run the software are:
- Keras 1.0.7
- Scikit-learn 0.17.1
- PyQt5 5.5.1
- Numpy 1.11.1
- SciPy 0.18.0
- Working C/C++ compiler

For easy installation on Windows, download and install [WinPython 3.4.4.4Qt5](https://sourceforge.net/projects/winpython/files/WinPython_3.4/3.4.4.4/). 

## Run the code
To run the code open a console in /scr and use:
```python
python main.py
```
