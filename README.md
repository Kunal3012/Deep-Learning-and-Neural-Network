# Deep-Learning-and-Neural-Network
to rvise the topics of DL &amp; NN

| Aspect                          | Neural Network                          | Deep Neural Network (DNN)                      |
|---------------------------------|-----------------------------------------|------------------------------------------------|
| **Number of Layers**             | Fewer layers (typically 1 or 2)         | Many hidden layers (typically > 3)             |
| **Number of Neurons per Layer**  | Limited                                 | Large                                          |
| **Architecture**                 | Shallow                                 | Deep                                           |
| **Representation Capability**    | Basic                                   | Complex, capturing intricate patterns         |
| **Computational Requirements**   | Moderate                               | Higher, requires more computational power     |
| **Learning Features**            | Limited hierarchical features          | Complex hierarchical features                 |
| **Use Cases**                    | Basic pattern recognition, classification| Image and speech recognition, complex tasks   |
| **Nature**                       | Foundation of machine learning          | Subset of machine learning, focuses on DNNs    |



In a neural network, each neuron is a computational unit that performs specific functions to process information. The operations within a neuron involve receiving inputs, applying weights, adding a bias, and applying an activation function. Let's break down the key functions of a neuron:

1. **Input Processing:**
   - **Inputs:** Neurons receive input signals from the outputs of neurons in the previous layer or directly from the input features of the data.
   - **Weights:** Each input is associated with a weight, which determines its significance in the computation. The weights are parameters that the neural network learns during training.

2. **Weighted Sum:**
   - **Calculation:** Neurons calculate the weighted sum of their inputs. This is done by multiplying each input by its corresponding weight and summing up these products.
   - **Bias:** A bias term is added to the weighted sum. The bias allows the neuron to adjust its overall activation level independently of the inputs.

3. **Activation Function:**
   - **Function:** The weighted sum with the bias is then passed through an activation function. The activation function introduces non-linearity to the neuron's response and determines the neuron's output.
   - **Common Activation Functions:**
     - **Sigmoid:** Transforms the output to a range between 0 and 1. Often used in the output layer of binary classification tasks.
     - **Hyperbolic Tangent (tanh):** Similar to sigmoid but maps values between -1 and 1. Commonly used in hidden layers.
     - **Rectified Linear Unit (ReLU):** Outputs the input for positive values and zero for negative values. Widely used in hidden layers due to its simplicity and effectiveness.
     - **Softmax:** Used in the output layer for multi-class classification, normalizing the outputs into probabilities that sum to 1.

4. **Output:**
   - **Result:** The output of the activation function represents the activation level of the neuron. This output is then transmitted to neurons in the next layer as input.

5. **Learning:**
   - **Adjustment:** During training, the neural network adjusts the weights and biases using optimization algorithms and backpropagation. This process helps the network learn to make more accurate predictions by minimizing the difference between predicted and actual outputs.

In summary, each neuron in a neural network acts as a processing unit that takes input signals, computes a weighted sum, adds a bias, applies an activation function, and produces an output. The arrangement and connectivity of neurons, along with the learned weights and biases, allow neural networks to learn and model complex relationships within the data, enabling them to perform tasks like regression, classification, or other types of information processing.
