# Active Learning in R: A Quick Introduction for Beginners
In this project, we aim to implement some baseline active learning strategies in R, experiment on a famous dataset Iris, 
highlight some insights and suggest future directions for active learning in the Statistics domain.

# Layout of Sources (with short descriptions)
```
Active_Learning_in_R
.
├── Active_Learning_in_R_Rcode.Rmd            (Source code)
├── iris.data                                 (data)
├── Active_Learning_in_R_Rcode_Simulation.pdf (Source code simulation using RMarkdown)
├── Active_Learning_in_R.pdf                  (A seemingly formal report)
├── Active_Learning_in_R_PPTslides.pptx       (A short talk and user guide)
├── Active_Learning_in_R_Presentation.mp4     (A short talk and user guide)
├── README.md
```

# Public Post
I also published this project in Medium if you are interested to look at [here](https://medium.com/@Andy1Wang/active-learning-an-exploratory-study-of-its-application-in-statistics-and-r-65713ccdad16)

# Experimental Settings
## Active Learning Querying Strategies
We implement two basic strategies "Uncertainty Sampling" and "Random Sampling". 
### Uncertainty Sampling 
Select the point with least confidence. One criteria is the point nearest to the current decision boundary.
### Random Sampling
Query the point randomly from the unlabeled pool.

## Model
The model we currently use is logistic regression, which is a classifier for binary classification problems.

