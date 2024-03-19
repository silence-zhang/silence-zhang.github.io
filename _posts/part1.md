###### Machine Learning(ML)
	The training of programs developed by allowing a computer to learn from its experience, rather than through manually coding the individual steps.
###### Neural Network(NN)
![[Pasted image 20240314180458.png]]
###### Parallel Distributed Processing(PDP)
- A set of processing units 
- A state of activation 
- An output function for each unit 
- A pattern of connectivity among units
- A propagation rule for propagating patterns of activities through the network of connectivities
- An activation rule for combining the inputs impinging on a unit with the current state of that unit to produce an output for the unit
- A learning rule whereby patterns of connectivity are modified by experience
- An environment within which the system must operate
###### Stochastic Gradient Descent (SGD: 随机梯度下降)
	Neural networks are special because they are highly flexible, which means they can solve an unusually wide range of problems just by finding the right weights. This is powerful, because stochastic gradient descent provides us a way to find those weight values automatically.
###### Training Loop
![[Pasted image 20240315111753.png]]
###### Feedback Loops 
1. A *`predictive policing`* model is created based on where arrests have been made in the past. In practice, this is not actually predicting crime, but rather predicting arrests, and is therefore partially simply reflecting biases in existing policing processes. 
2. Law enforcement officers then might use that model to decide where to focus their policing activity, resulting in increased arrests in those areas. 
3. Data on these additional arrests would then be fed back in to retrain future ver‐ sions of the model.
This is a positive feedback loop: the more the model is used, the more biased the data becomes, making the model even more biased, and so forth.
###### Classification and Regression
	A classification model is one that attempts to predict a class, or category. That is, it’s predicting from a number of discrete possibilities, such as “dog” or “cat.” 
	A regression model is one that attempts to predict one or more numeric quantities, such as a temperature or a location.
###### Overfitting and Underfitting
	confirmed that overfitting is occurring (i.e., if you have observed the validation accuracy getting worse during training).

![[Pasted image 20240315115211.png]]
###### Convolutional Neural Network (CNN)

###### Pre-trained Model
	A model that has weights that have already been trained on another dataset is called a pre‐ trained model.
###### Transfer Model
	Using a pretrained model for a task different from what it was originally trained for.
###### Fine-Tuning(adapt a pre-trained model for a new dataset)
	A transfer learning technique that updates the parameters of a pre‐ trained model by training for additional epochs using a different task from that used for pretraining.
######  Deep Learning Vocabulary
![[Pasted image 20240315144530.png]]
###### Training Sets && Validation Sets && Test Sets
- Training data is fully exposed, 
- Validation data is less exposed
- Test data is totally hidden
###### Independent Variables && Dependent Variables
	The independent variable is the thing we are using to make predictions from, and the dependent variable is our target.
###### Data Augmentation
	Data augmentation refers to creating random variations of our input data, such that they appear different but do not change the meaning of the data.
###### Out-Of-Domain data
	That is to say, there may be data that our model sees in production that is very different from what it saw during training.