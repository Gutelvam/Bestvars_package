<h1>Best Variables for classification and regression models</h1>

The objective of this packege is to simplify the usage of methods to make feature selection.

The Package **bestvarspk** is a Python module for machine learning built based on top of sklearn feature_selection and is distributed under the  license.

The project was started in 2020 by Gutelvam as a Udacity Nanodegree of project.

<h4>Installation</h4>

***Dependencies***

bestvars_pk requires:

        -Python (>= 3.6)

        -NumPy (>= 1.13.3)

        -SciPy (>= 0.19.1)

        -joblib (>= 0.11)

        -threadpoolctl (>= 2.0.0)

        -scikit-learn (>=0.23.1)

        -matplotlib(>=3.2.2)

        -seaborn(>=0.10.1)

        -pandas(>=1.0.3)

***User installation***


If you already have a working installation of scikit-learn, the easiest way to install is using pip available in : https://pypi.org/project/bestvarspk/
 >!pip install bestvarspk

<h2>How to use</h2>

        1. Instantiate an objet 'Selection'
                from bestvarspk.Variables_selection import Selection
                obj = Selecton(df, target)
where:

**df** is a dataframe 

**target** is a string of target column name    

        2. Use methods available.

                obj.corr_features()

                obj.importance_features()

                obj.rfe_features()

obs: Anytime you can check for help(?) to check docstrings.
