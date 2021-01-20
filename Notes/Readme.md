# Notes for getting a better idea of the excercise answers

## Chapter-1 The Machine Learning Landscape

### What is Machine Learning?

**General Definition**:
> Machine Learning is the field of study that gives computers 
the ability to learn without being explicitly programmed. 

**Engineering Definition**:
> A computer program is said to learn from experience E with respect to some task T
and some performance measure P, if its performance on T, as measured by P, improves
with experience E.

### Types of Machine Learning Systems
- Whether or not they are trained with human supervision (supervised, unsuper‐
vised, semisupervised, and Reinforcement Learning)
- Whether or not they can learn incrementally on the fly (online versus batch
learning)
- Whether they work by simply comparing new data points to known data points,
or instead detect patterns in the training data and build a predictive model, much
like scientists do (instance-based versus model-based learning)

>> Fun fact: this odd-sounding name is a statistics term introduced by Francis Galton while he was studying the
fact that the children of tall people tend to be shorter than their parents. Since children were shorter, he called
this regression to the mean. This name was then applied to the methods he used to analyze correlations
between variables.

#### Important Supervised Learning algorithms:
- k-Nearest Neighbors
- Linear Regression
- Logistic Regression
- Support Vector Machines (SVMs)
- Decision Trees and Random Forests
- Neural networks

#### Important  Unsupervised learning algorithms:
- Clustering
  - k-Means
  - Hierarchical Cluster Analysis (HCA)
  - Expectation Maximization
- Visualization and dimensionality reduction
  - Principal Component Analysis (PCA)
  - Kernel PCA
  - Locally-Linear Embedding (LLE)
  - t-distributed Stochastic Neighbor Embedding (t-SNE)
- Association rule learning
  - Apriori
  - Eclat
  
#### Semisupervised learning 
algorithms used in scenarios like google photos where the software clusters and recogises people from the photos and then ask u to label few photos.
  
#### Reinforcement Learning
Its a little different way of teaching an algorithm. It contains an aganet and an envirnment where the agent can interact and learn based on the rewards offered by the envirnment. Google's alpha zero and go are the best examples of reinforcement learning.


#### Batch and Online learning
Another criterion used to classify Machine Learning systems is whether or not the
system can learn incrementally from a stream of incoming data.

#### Batch Learning
In batch learning, the model is trained and put into production. It wont train again. So the training process is done offline, therefore the name offline learning

#### Online Learning
The training happens incrementally. The model keeps on training on the new data but it must preserve the old state also. If we train the spam detection model with only new type of data, it will miss out the old type of spams. So it is important to keep the balance. One of the other place where online learning is applied when the data is too huge that it can't fit in a computer memory such type of training of data is known as out-of-core learning. The data is divided into mini-batches and used in training the system.


