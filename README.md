This is a multi-instance regression problem in which we have to predict a value called rain quantity based on the output of six photosensors.  
I used a pre-processed training set in which the input is aggregated using some statistics like min, max, mean, std deviation and so on (there are multiple values for each second and I have aggregated them).  
I implemented a form of stacking with two base classifiers and a simple metalearner, a linear regression learner.  
