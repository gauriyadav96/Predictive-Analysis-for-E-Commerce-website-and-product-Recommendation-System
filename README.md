# Predictive-Analysis-for-E-Commerce-website-and-product-Recommendation-System


* A master csv by the name "Replaced.csv" is provided which contains the initial dataset on which this project is based.
  (Download the CSV files from https://drive.google.com/open?id=1EOsLs2U60tZ3lKCmZOG6CHC3-GEtR5R2)
* For building a recommendation system, we use different set of algorithms for getting the results such as product recommendation and 
content matching reviews of the users.
* All the files are in .py format and need to be executed using Jupyter Notebook
* Topics like RNN, ALS, Clustering, Naive Bayes need to be executed in Databricks which provides the use of Apache Spark for faster processing of these algorithms.
* We need to setup a tensorflow environment in the anaconda prompt 
 

# In order to create a virtual python environment, follow the given steps:
1) open anaconda prompt
2) type "conda create -n ads_project anaconda"
3) To activate this environment, use:  activate ads_project
4) type "pip install --ignore-installed --upgrade tensorflow"   
5) type "conda install -c conda-forge keras"
6) for virtual environment if u dont see tensorflow as backend then type "set KERAS_BACKEND=tensorflow"
7) install jupyter notebook: "pip3 install jupyter"
8) use the command "set KERAS_BACKEND=tensorflow"
9) type 'jupyter notebook'
10) To deactivate an active environment, use: deactivate

# Following libraries need to installed by running the given code in anaconda prompt:
1) python -m pip install wordcloud
2) pip install -U nltk
3) pip3 install --upgrade colorama
4) pip install h2o
5) pip install -U imbalanced-learn
6) pip install -U gensim
7) pip install scikit-surprise
