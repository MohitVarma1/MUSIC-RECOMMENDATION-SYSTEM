# MUSIC-RECOMMENDATION-SYSTEM

MUSIC RECOMMENDATION WITH GRADIENT DESCENT AND LINEAR REGRESSION
The goal of this project was to provide recommendation with collaborative filtering, but implementing our own Linear regression, gradient descent.
What makes our project Unique is that we have used Pyspark to parallelize the linear regression we have implemented on our own by using dataframes.
There is a runnable Ipython Notebook currently, which can be run for the initial Proof of Concept.
For the demonstration we will have a webpage with recommendations for rated music.
The files included are the code necessary for the task.

Running the Experiments
pip install requirements.txt
python recommend_engine.py (Least squares and SGD)
python recommend_genres.py (Genre Recommendation using Logistic Regression)
