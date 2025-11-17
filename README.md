# Noise Predictor
This repository contains my group Empirical Risk Maximisers' submission for the group project for **CS421: Principles of Machine Learning**. We train both regression and classification models to predict the noise level and anomaly type of users, in corrupted movie-rating data. 

We begin with exploratory data analysis and feature engineering in `EDA.ipynb`. 

You can then follow our group's progress from `PROJECT_week9.ipynb` through to  `PROJECT_week12.ipynb`, which was the final submission for the project. 

# Takeaways
Throughout the project, we encountered a few challenges in our end-to-end workflow, which led to poorer-than-expected performance at some milestones.  

Most notably, we engineered some of our features using the full dataset rather than only the training split, resulting in unintended data leakage.   
In addition, we used some models without fully understanding their assumptions or compatibility with our data.

Despite the setbacks, these experiences have been valuable learning points, and we will carry them forward as we continue our journey as aspiring machine learning engineers! 

<p align="center">
  <img width="75%" src="https://pbs.twimg.com/media/Em9PAabW8AI8NR4.jpg"
  alt="Banner">
</p>