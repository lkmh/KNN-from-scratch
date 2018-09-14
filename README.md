**What is k-Nearest Neighbours ?**    
k-Nearest Neighbours finds the most similar training examples (how close in terms of Euclidean distance) with the test examples.     
It classifies the test examples by a majority vote among the k-most similar examples  


k-Nearest Neighbours is a non-parametric and a lazy algorithm 
>Non-parametic: Does not make any assumptions about the distributions of the underlying data    
>Lazy : Does not use the training data points to do any generalization i.e. It is fast 

**Implement k-Nearest Neighbours from Scratch in Python **
​
1) Load the Iris data set   
2) Split into training and test dataset and convert to numpy arrays   
3) Functions: 
> 3a) Create function to find the Euclidean distance between Test example and training example      
> 3b) Create function to find the k - nearest training examples from the test example       
> 3c) Create function to count votes the classification of k-nearest training examples and the maximum votes is the prediction      
> 3d) Creat function to get accuracy from the prediction and test results   
​
4) Create a function that run 3 functions for each test example  
