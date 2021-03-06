# mit-futuremakers

## Responses
1. [7-6-2021](#7-6)
2. [7-7-2021](#7-7)
3. [7-8-2021](#7-8)
4. [7-9-2021](#7-9)
7. [7-12-2021](#7-12)
8. [7-13-2021](#7-13)
9. [7-14-2021](#7-14)
10. [7-15-2021](#7-15)
11. [7-16-2021](#7-16)
14. [7-19-2021](#7-19)
15. [7-20-2021](#7-20)
16. [7-21-2021](#7-21)
17. [7-22-2021](#7-22)
18. [7-23-2021](#7-23)
19. [7-26-2021](#7-26)
20. [7-27-2021](#7-27)
21. [7-28-2021](#7-28)
22. [7-29-2021](#7-29)

  
  

<a name="7-6"></a>
### Day 1: 7-6-2021              
<p>I hope to learn more about the applications of AI and how to implement it within projects. I don't understand a lot about AI algorithms and I want to be able to implement them into my own applications. Additionally, I hope to learn more abou the theory behind ideas like neural networks and deep learning as well as its future potential.</p>
I learned about the interconnetions and professions within STEM as well as with computing. My focus group discussed the differences and similarities between these fields, which I found intriguing. Although all these subjects employ logic, one of my peers highlighted the differences in the ways they incorporate creativity. I think they all solve problems but take different processes and steps to reach a conclusion. 
  
  

<a name="7-7"></a>
### Day 2: 7-7-2021 
Public Narrative
- Story of self: call to leadership
- Story of now: strategy and action
- Story of us: shared values and shared experience  

Story of self: Challenge, Choice, Outcome, Moral  
Challenge: being behind my peers in flute  
Choice: choosing to work harder  
Outcome: feeling proud of my work  
Moral: practice makes perfect, hard work pays off  
https://www.youtube.com/watch?v=Wc3KcMzPwFM  

I learned about the importance of creating a public narrative in order to engage your audience. This skill can be employed to connect with the audience and create a positive change in your community -- as with the case of xxx whose combined story of self, now, and us led him to be able to build a middle and high school in his home village through donations. To be frank, I'm confused as to how it relates to leadership but still enjoyed the experience and learned about how to create my own story! Nevertheless, I really enjoyed Dr. David Kong's seminar and hope I can carry these skills onward.
  
  

<a name="7-8"></a>
### Day 3: 7-8-2021     
Hierarchy
- Artificial Intelligence
    - Machine Learning  
        - Neural Network
            - Deep Learning

| Supervised ML | Unsupervised ML |
| ----------- | ----------- |
| Trained on labelled data to extrapolate | Trained on unlabelled data to find patterns and relationships |
| Used for classification and regression | Used for clustering |
| Can be difficult and time-consuming to label datasets | Can have inaccuracies and find irrelevant relationships |  

Scikit-Learn cannot visualize data without other data analysis librararies because Scikit-Learn is built to model data through supervised and unsupervised machine learning data. The module is built upon SciPy and therefore requires additional libraries to visualized data.
  
  

<a name="7-9"></a>
### Day 4: 7-9-2021   
I learned a lot about how deep learning works and what exactly Tensorflow and Tensor Processing Unit is.  
One real world problem I've thought about is fraud and how people can sign fake signatures. By using ML to analyze a person's signature (or handwriting perhaps) the algorithm would be able to analyze the match between two samples. 
  
  

<a name="7-12"></a>
### Day 7: 7-12-2021     
Numpy: used for array manipulation  
Scikit-learn: used to create ML models  

Tensors: multi-dimensional arrays with uniform type
- Shape: length of each axes
- Rank: number of tensor axes
- Axes or dimension: dimension of tensor
- Size: number of items in a tensor  

Tensorflow vs. Pytorch  
Tensors are multi-dimensional arrays and are used in machine learning to encode multi-dimensional data. For example, a 3D space would require three dimensions: height, width, and depth. While most data can be represented through an array or matrix, tensors can often be the more intuitive and simple data structure depending on the data.  

In the tutorial, I noticed that using Tensorflow, matplotlib, and other ML libraries allows the program to perform a lot of different functions. For instance, it is much simpler to create a graph/plot of data and output the result. Additionally, user Tensorflow allowed for a simple neural network to be created in just a few lines. While it is important to understand the underlying concepts, ML libraries make it easy to program a neural network.  
  
  

<a name="7-13"></a>
### Day 8: 7-13-2021     
Artificial Neural Networks  
Activation function: determines the threshold that neuron is activated and strength of signal  
Weights are the strength of the node. Biases shifts the activation function up or down (similar to constants in functions).  
- Feed-forward
- Backpropagation (optimizes weight to learn from errors)
- Recurrent
- Perceptron
  
  

<a name="7-14"></a>
### Day 9: 7-14-2021     
Convolutional Neural Network (CNN): feed-forward artificial neural network. Element-wise matrix multiplication (dot product) occurs between pixel value with filter size. Often used for computer vision  
Kernel: a filter  
Activation function: used to find features that are not given in data  
Rectified Linear Unit (ReLU) layer: nonlinear function, no parameters or weights given, output is a rectified feature map  
Pooling operation/layer: input is rectified feature map, down-sampling (shrinking the iimage) to reduce dimensionality and computational complexity (mitigates overfitting, helps to identify relevant information of image  
- Max pooling: largest element is taken from feature map
- Average pooling: average of elements in a section of image  

The convolutional layer creates a feature map with matrix multiplication, the activation layer uses activation functions, and the pooling layer refines the feature map with max/average pooling  
After multiple lays (convolution + ReU, pooling, convolution + ReLU, pooling...) the resulting feature maps are input into fully-connected layer  
Fully-connected layer: mathematically sums the feature from all combinations of the features to prepare for classification (does not include activation layer)
  
  

<a name="7-15"></a>
### Day 10: 7-15-2021     
Algorithmic Bias and Data Sets  
Bias is simply a reflection of the training datasets  
- Sample bias
- Exclusion bias
- Measurement bias
- Observer bias
- Association bias
- Recall bias  

Data should represent "what should be" rather than "what is".  
A form of data governance should be mandated and enforced.  
Model evaluation should include generalization across groups.  

https://www.survivalofthebestfit.com/
1. How do you think Machine Learning or AI concepts were utilized in the design of this game?  
The game was designed to demonstrate the effects of AI bias. I think these concepts were used to build the premise of the game and bring up a serious issue in the field of technology. It shows the consequences if AI bias continues unchecked.  

2. Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, and equitable? Please reflect on why you selected this specific biased model.  
One real world example is how Google Translate can better translate more well-known languages rather than other specific, perhaps regionally spoken languages. This happens as a result of sample bias, since these languages don't have as much data surrounding them and are not used as often. This model can be made more equitable by collecting more data to balance the training data or through ata augmentation. Data augmentation can be especially helpful in computer vision, however may be applicable in NLP. I chose this example because it applies to me to a certain extent. As a Chinese-American, I sometimes find Mandarin translations to be inaccurate. While Mandarin is still a very commonly spoken language, it still has issues, therefore meaning that lesser known languages are even more greatly affected.  
  
http://gendershades.org/overview.html
1. Discuss some of the ways that you intend to avoid algorithmic bias when constructing AI projects.
Algorithmic bias can be avoided by using diverse and inclusive training data as well as developers. Additionally, comprehensive testing must be performed before release to evaluate the efficacy and possible biases of the model. 
  
  
<a name="7-16"></a>
### Day 11: 7-16-2021   
|  | Convolutional Network | Fully Connected Neural Network |
| --- | ----------- | ----------- |
| Layers | - Convolutional layer <br /> - Pooling layer <br /> - Fully connected layer | - Series of fully connected layers |
| Role | Creates feature map (extracts features) | Connects every neuron in one layer to every neuron in the other layer |
| Applications | Most used for computer vision (image search, facial recognition, etc.) | Broadly applicable as it is structure agnostic |  

https://medium.com/swlh/fully-connected-vs-convolutional-neural-networks-813ca7bc6ee5

  
  
<a name="7-19"></a>
### Day 14: 7-19-2021   
We learned about loss functions, which really helped to explain another aspect to evaluate in our ML models. Rather than simply taking into account the accuracy, the loss functions allow developers to understand how the model can be improved. I didn't know that there were ways to evaluate the loss function based on the confidence of the model's answer. We also learned about model optimization, which is especially important since different parameters of the model can always be improved. My mentor explained these aspects in my code, helping me understand what we learned in context.
  
  
<a name="7-20"></a>
### Day 15: 7-20-2021   
Activation Functions  
Although we learned about activation functions before, we dove deeper into the topic, learning about the various types and how they actually work. While it got a bit confusing with the different types and the math behind them, I understand the general concept. I think the most important aspect is being able to look at the model and determine which activation function to use since they all have different properties which can significantly change the output. 

Rectified Linear Activation Function (ReLU)  
ReLU is the most commonly used activation function for a number of reasons. Firstly, it diminishes the vanishing gradient problem. Since the gradient (derivative) of the ReLU function can only be 0 or 1, there is no vanishing gradient. Another benefit of the ReLU activation function is that it is less computationally expensive when compared to sigmoid or tanh functions since it has simpler mathematical operations. One use case for the ReLU function is almost anythin as it is by far the most commonly used activation function. For example, it is very often used to train the models with the mnist database.  

  
  
<a name="7-21"></a>
### Day 16: 7-21-2021  
Ethics-Driven Machine Learning  
"Garbage-in, garbage-out"  
Why are algorithmic details not disclosed?  
- sensitive data
- making system vulnerable
- harm company property rights
- opacity of algorithms (blackbox)
- conflict between accuracy and individual rights/autonomy  
  
Fairness vs. Accuracy  
By using the COMPAS system as an example, I was able to learn about the prevalence of bias in AI and the obstacles in overcoming it. It wasn't as simple as I initially thought as it is dependent on a huge number of factors and even being aware of these aspects is not enough to address the problem. It was interesting to learn about the different types of biases as they can originate from different sources as well as have different effects on the model.
  
  
  
<a name="7-22"></a>
### Day 17: 7-22-2021   
Today, we learned about image classification and the ways in which data must be pre-processed and how the layers should be set up to produce a meaningful output. I haven't gotten to the action items for today but will elaborate more once I have run actual code.  
  
We also had a seminar with Dr. Jennifer Chu-Carroll. Her presentation was extremely interesting as she dove into the NLP projects she has worked on, including the Watson Jeopardy! project. By demonstrating the progress and the obstacles of the project, I learned a lot about AI! She showed us that while the technology was used on a game show, it had potential to help children with reading comprehension. Additionally, she described the challenges they faced, such as the explainability of the model, misunderstandings of jargon, and connecting synonyms/entailment. However, the technology she described was still incredibly advanced and intriging to learn about. Really inspiring!  
After that, she continued to explain her more recent projects, such as the virtual travel agent software. The chat function she showed us seemed incredibly advanced and very natural. Her work is truly inspiring! Maybe I'd like to go into NLP?


  
<a name="7-23"></a>
### Day 18: 7-23-2021  
  
  
  
<a name="7-26"></a>
### Day 19: 7-26-2021  
Autoencoder: neural network that learns data representations through unsupervised manner (latent space, hourglass shape)    
- Data-specific
- Lossy
- Automatic  

1. Encoder: learns the compressed representation of input data
  - Decreases number of features (downsampling)
  - Information lost from decrease in features (dimensions)
  - Features (data) that remains is "important"  
3. Decoder: reconstructs input data by depressing compact representation
  - Takes lower dimension to higher dimension (upsampling)
  - Input cannot be recreated because of loss of information
  - Goal: output is same as input, reduce dimension of data while not losing information, minimize reconstruction loss

Applications: complex data (many features), dimensionality reduction, data denoising, feature estimation, generation of synthetic data  
  
Variations
- Convolutional: each layer is a CNN *
- Variational (VAE): distribution of data *
  - Constructs probability distribution of each feature
- Denoise: feature extractor, determines important parts and loses noise in image 
  
  
Upsampling (Unpooling)
- Nearest Neighbor
- Bed of Nails
- Bi-linear Interpolation
  
  
  
<a name="7-27"></a>
### Day 20: 7-27-2021  
Applications of Affective Computing  
1. As presented by Dr. Ajjen Joshi, one application could be detecting drowsiness when driving. This involves an ML model that uses computer vision to analyze the facial expression/features of the driver.
2. Another application could be in the field of teaching. By using ML to analyze the learning patterns of students, the model can predict the best learning method for various subjects and students.  
  
  
  
<a name="7-28"></a>
### Day 21: 7-28-2021  
NLP
  
  
  
<a name="7-29"></a>
### Day 22: 7-29-2021  
Computer Vision 
- Image classification (with localization)
  - Localization: outlines object with box
- Object Detection
  - Multiple objects
- Object Segmentation
  - Segmentation: assigns pixels to object
  - Semantic Segmentation: assigns a label to each pixel
  - Instance Segmentation: differentiates all instances in each class
- Object Tracking: following object over tiime
- Pose Estimation: deducing joints of body
- Image Generation
- Image Style Transfer
- Image Colorization
- Image Reconstruction
- Image Super-Resolution
- Image Synthesis
  - Deep fakes
- Image Enhancement
- Face detection, recognition, verification
- Emotion Detection (affective computing). 

Generative Adversarial Networks (GANs)
- Generator model learns to generate plausible data
  - Ex. CNN
- Discriminator model: distinguishes generator's data and real data
  
  
  
  
<a name="7-30"></a>
### Day 23: 7-30-2021  
  
  
  
  
  
  
  
