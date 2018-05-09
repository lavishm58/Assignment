## Setup ##
## Using virtual environment ##
Below intructions are given for installing technologies used
* Install python pip and virtualenv

```
sudo apt-get install python2.7 python-pip
pip install virtualenv
```
* Setup virtual env and Install jupyter notebook

```
virtualenv -p python venv_py
source venv_py/bin/activate
pip install jupyter
```
* Install dependencies needed (python libraries)

```
pip install -r requirements.txt
```

## Understanding Files ##

* MainCode.ipynb contains the code from which all other files are obtained.Also, it is well documented.

* MainCode.ipynb has two approaches FuzyMatching And Training with Classifiers.

* There are two sample inputs -
  * Deduplication Problem - Sample Dataset.csv is the provided one.
  * ManualLabelsorted.csv is the manually labeled Cluster ID column for calculating Accuracy.

* Output Files for all the approaches are there in output folder with similar names of them - 
  * -- output files have clusters with their ID and confidence score for it.
  * -- final_output files have unique ID's by keeping first and removing all other duplicate observation
  * -- FuzzyOutput file has output for fuzzy Matching Approach.
* Detailed approach is also written in approach.pptx.
