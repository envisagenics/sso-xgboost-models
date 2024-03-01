# sso-xgboost-models

This repository contains python pickle files (created using the python pickle module: https://docs.python.org/3/library/pickle.html), that are the serialized files of the trained XGbooxt machine learning models:

upstream_intron_model.pkl
downstream_intron_model.pkl
exon_model.pkl

The python modules needed to create and run these files are as follows:
numpy 1.19.5
scipy 1.5.4
scikit-learn 0.22
xgboost 0.28
joblib 1.0.1

These models can be used in combination with features of interest for a particular event to predict the effect of a single nucleotide on proximal exon inclusion. 
