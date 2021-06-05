
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using Python version 3.0 or older.
Libraries that were used for the analysis are Pandas, Numpy, Matplotlib, Seaborn, and Scikit-learn.


## Project Motivation<a name="motivation"></a>

As part of the Udacity Data Scientist Nanodegree, I read the post by Josh under https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711 which gave some instructions on how to become a developer. Afterwards, I started to wonder whether satisfied individuals in this field share any common traits.

To this end, I analyzed the 2020 Stack Overflow Developer Survey (https://insights.stackoverflow.com/survey) and focused on the salaries, working hours, and coding experience of developers. Identifying some common traits could provide novices in the field with some guidelines regarding which jobs to pursue to become satisfied themselves.

I explored the following questions:
2. Are developers with a higher salary more satisfied?
3. To which extent do the working hours influence job satisfaction?
4. Do experienced programmers tend to be more satisfied than their less experienced colleagues?

In addition to these questions, which are also addressed in the related Medium post under (...), I explored whether using these three variables, one could build a machine learning model that enables predicting job satisfaction of developers. To this end, I tested a logistic regression, a decision tree, and a random forest model.


## File Descriptions <a name="files"></a>

The Jupyter notebook analyzing_job_satisfaction.ipynb provides all the code that was used for the analysis.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711).
The results indicate that satisfied developers represent a heterogenous group consisting of individuals working both short and long hours and either being decades long experts in their field or having started only some years ago. Only a higher salary seems to be related with job satisfaction. Furthermore, the exploration revealed that the three examined variables do not enable to build a good machine learning model to predict job satisfaction.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I want to give credit to Stack Overflow for the data. Also, I relied on numerous posts on Stack Overflow when stuck with any question. I also want to thank Josh and the rest of the Udacity team for providing this code, the very useful instructions and guidelines for completing this project. 
Otherwise, feel free to use the code here as you would like! 

