# Simulations and Machine Learning of Random Walk with Poisson Distributed step sizes
The goal of this project is to observe how accurate the computer can be when given two similar distributions. We will create two distributions for the machine to distinguish: one is our Poisson distributed step size while the other is just our normal random walk multiplied with the same lamda as Poisson distributed step size. We will also be using supervised learning, specifically the logistic regression, to classfy our distributions. 
# Packages Required
Sci-kit learn, RandomForest, Cross Validation, and Pandas (this is mainly for the supervised learning part, everything else is provided)
# What is a Random Walk? And why are we using Machine Learning(specifically supervised learning)?
Random walk is a process which models the behavoir of the movement of the object(in step sizes) over a certain period of timesteps. We wanted to use random walk as data for our machine learning because of two reasons. One is majority of objects, particles, or even living things, have movements similar to that of random walk. Another reason is this happens to be my undergraduate physics research. Our reason behind using supervised learning is because we were in our earliest stages of research so we chose a simple and quick method of analyzing data.
# Derivation for a regular random walk model
For a regular one dimensional random walk model, imagine flipping a coin. The coin has a probability of q (some arbitary variable) of being face up while the coin has a probability of p being face down. We can establish the relationship that the sum of all probabilities has to be 1, so q in terms of p is q=1-p. Then we assign the number of steps taken, or retracted, when this coin flipping occurs. For a simple case, if the coin is up then the walker takes a step forwrd and if down the walker takes a step back.
