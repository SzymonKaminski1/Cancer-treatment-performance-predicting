# Cancer treatment performance predicting
This project is about choosing best model for predicting cancer medicine perfomace. Data set consists of variables containing information about cancer genes expression and a variable 'Y' showing medicine effect. 'Y' values are in [0,1] interval and the lower 'Y' value is the better medicine is performing.\
Train and test data is stored in: https://drive.google.com/drive/folders/1ADea54376PHXMwRHeteK6h4kqqPxS5af?usp=sharing \
There were three models I had to check: Lasso, ridge regression and random forest. For checking Lasso and ridge regression I used Elastic Net method, and for random forest I used 500 variables with highest coefficient of variation.\
I used pandas and sklearn libraries.
* project.ipynb\
This project was scored at my university course. I got max points for my prediction, overall project mark was 88%. 
* project_improved.ipynb\
This is improved version of my university project. I added data standardization, preliminary function that uses Ridge, Lasso and ElasticNet methods to obtain view on how these algorithms perform on given data set and further checking for, in my opinion, best candidate for model and its parameters. These elements enabled me to create more efficient way to train these models and eventually get smaller MSE value on the training data set. Unfortunately I am not able to check my results on test set any more.
