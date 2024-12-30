## Multi-Layer Perceptron

- What is MLP?
    - MLP is a type of neural network that consists of multiple layers of neurons.
    - It's hard to understand the MLP model, actually I also don't understand it very well. In MLP it has a input layer, hidden layer and output layer. The main process of MLP is hidden layer.
    - All process : Input -> Hidden Layer -> Output Layer.

- The structure of MLP
    - The structure of MLP is like this -> and also the picture is my understanding of the MLP:

        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 300">
        <rect width="500" height="300" fill="white"/>
        <g stroke="black" stroke-width="1">
        <line x1="130" y1="110" x2="250" y2="90"/>
        <line x1="130" y1="110" x2="250" y2="150"/>
        <line x1="130" y1="110" x2="250" y2="210"/>
        <line x1="130" y1="200" x2="250" y2="90"/>
        <line x1="130" y1="200" x2="250" y2="150"/>
        <line x1="130" y1="200" x2="250" y2="210"/>
        <line x1="280" y1="90" x2="400" y2="150"/>
        <line x1="280" y1="150" x2="400" y2="150"/>
        <line x1="280" y1="210" x2="400" y2="150"/>
        </g>
        <g>
        <circle cx="115" cy="110" r="15" fill="white" stroke="black" stroke-width="2"/>
        <circle cx="115" cy="200" r="15" fill="white" stroke="black" stroke-width="2"/>
        <circle cx="265" cy="90" r="15" fill="white" stroke="black" stroke-width="2"/>
        <circle cx="265" cy="150" r="15" fill="white" stroke="black" stroke-width="2"/>
        <circle cx="265" cy="210" r="15" fill="white" stroke="black" stroke-width="2"/>
        <circle cx="415" cy="150" r="15" fill="white" stroke="black" stroke-width="2"/>
        </g>
        <g text-anchor="middle" font-family="Arial">
        <text x="50" y="155">Input Layer</text>
        <text x="265" y="70">Hidden Layer</text>
        <text x="420" y="130">Output Layer</text>
        </g>
        </svg>

- Input Layer
    - The input layer is the first layer of the MLP. it is the layer that receives the input data.
    - But the number's neuron in input layer, it's not the same as the number of features in the dataset.
    - For example, if we have a dataset with 784 features, the number of neurons in the input layer is 784.
    - Then why the number of input layer's neuron us 784? -> As a picture, if the picture is 28 pixels * 28 pixels, then the number of neurons in the input layer is 784. All of the pixels are transformed into a vector.
