# d2l notes 

## Part 1 - An introduction 
## Key components 
The main difference between machine learning and traditional approaches to programming is that you don't need to think in advance about every single edge case. 
There are multiple cases where thinking about the "business logic" in such details is required, for example when writing web apps or when you describe any user centric process.
But there are some short-comings to this approach, if you want to model a more complex problem like predicting weather, where you can't accurately think in advance of every edge case.
That's where neural networks shine. 
In order to do that you need to follow a couple of steps:
1. Start off with a randomly initialized model that cannot do anything useful.
2. Grab some of your data 
3. Tweak some knobs so that it performs better the next time
4. Repeat until satisfied 

We can split these tasks into key components of a learning system:
1. __*Data*__ that we can learn from 
2. ___Models___  that transform data 
3. An ***Objective Function*** that quantifies how the model is doing 
4. An ***Algorithm*** that adjust the parameters of the model to optimize for the objective function. 


## Kinds of ML problems 

### Supervised learning 

--> Regression - approximating how much or how many some task would take 
--> Classification - which one is it?
-> Tagging ? Which classes are in the current data batch? Non-exclusive multi-label classification problem 
-> Search ? Which one is relevant for the query 
-> Recommender System ? An emphasis is put on the personalization of the app to the user - music recommendation etc
-> Sequence Learning 

### Unsupervised learning 

--> It can be unsupervised or self-supervised
--> You can have someone else decide if you were succesful or not 

### 
