# Photonic-Crystal-Fiber
The field of photonics has witnessed significant advancements in recent decades, marked by 
numerous breakthroughs and innovations. A pivotal component of photonics, photonic crystal 
fiber (PCF), has garnered considerable attention for its ability to confine light within a narrow 
range and manipulate its characteristics. This thesis focuses on the optical properties of D-Shape 
photonic crystal fibers, which have emerged as a prominent area of research due to their 
compatibility with conventional optical fibers and versatility in supporting various modes. 
 
However, accurately determining the optical properties of D-Shape PCFs presents challenges 
owing to their intricate geometry and material composition. To address this, we propose a machine 
learning-based model aimed at predicting the optical properties of D-Shape photonic crystal fibers. 
Our methodology entails training machine learning models using a dataset of simulated optical 
properties, enabling accurate predictions for new fibers. 

----------------------------------------------------------------

Additionally, traditional numerical methods like the Finite-Difference Time-Domain (FDTD) 
method and beam propagation method are employed to compute PCF optical properties. However, 
these methods, while accurate, are often computationally intensive and time-consuming, 
particularly for PCFs with complex geometries. 

 it introduces a groundbreaking ML methodology tailored specifically for computing the 
optical properties of D-shape PCFs. This novel approach surpasses traditional numerical methods 
in terms of both speed and accuracy. Leveraging a curated dataset of simulated optical properties, 
the ML model, powered by a neural network algorithm, discerns intricate relationships between 
input data and the optical characteristics of D-shape PCFs. The implications are profound, offering 
a streamlined path for designing and optimizing D-shape PCFs for a multitude of applications, 
spanning from fiber-optic communication to sensing and laser technology.

--------------------------------------------------------------
*DataSet*

![image](https://github.com/Prajwal-101/Machine-Learning-model-for-predicting-the-optical-properties-of-a-D-Shape-PCF/assets/159109640/a954fcfc-2656-4e74-818f-95172e212085)


--------------------------------------------------------------

**Machine learning Models**

*1. Artificial Neural Networks (ANNs):*

Artificial Neural Networks (ANNs) are computational models inspired by the structure and functioning of the human brain. ANNs consist of interconnected nodes (neurons) organized in layers: input layer, hidden layers, and output layer. Each neuron receives input signals, processes them using an activation function, and produces an output signal. During training, ANNs adjust the weights of connections between neurons to minimize the difference between predicted and actual outputs. ANNs are capable of learning complex patterns from data and are widely used in various tasks, including regression, classification, and pattern recognition.

ReLU Activation Function in ANN: 
ReLU (Rectified Linear Unit) is a popular activation function in neural networks. It's simple, efficient, and effectively handles the vanishing gradient problem. However, it can lead to dying neurons.

Adam Optimizer:
Adam optimizer combines the benefits of AdaGrad and RMSProp. It adapts the learning rate for each parameter, includes momentum optimization, and is robust to noisy and sparse gradients. It's widely used due to its effectiveness and ease of use.

Hyperparameter Tuning in ANN: 
Hyperparameter tuning involves selecting optimal settings for parameters like learning rate, batch size, and network architecture. It's crucial for maximizing model performance but can be computationally expensive. Techniques like grid search or random search are used to systematically explore the hyperparameter space and find the best configuration.

*2. Random Forest Regressor:*

Random Forest Regressor is an ensemble learning technique used for regression tasks. It constructs multiple decision trees during training and outputs the average prediction (regression) of individual trees. Random Forest is robust to overfitting, as it combines predictions from multiple weak learners (decision trees) to reduce variance. Each decision tree in the Random Forest is built from a random subset of features and training data, which promotes diversity among trees. Random Forest can handle both numerical and categorical data and is capable of capturing complex relationships between features and target variables. It's known for its flexibility, scalability, and ability to provide feature importance’s for interpretation.

