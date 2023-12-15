# Deep Neural Network



Conventional methodologies employed in detecting distributed denial-of-service (DDoS) attacks have frequently struggled to adapt to the dynamic and multifaceted evolution of such threats. Furthermore, many of the contemporary detection and prevention solutions, while innovative, remain anchored to dedicated workstations, lacking the flexibility and scalability required in today's digital landscape. To bridge this technological chasm, this research introduces a state-of-the-art Intrusion Detection System (IDS) firmly rooted in advanced Deep Learning techniques. By leveraging the expansive and adaptable nature of cloud-centric, service-oriented architectures, we not only bolster detection precision but also offer a solution designed for modern infrastructures. This system provides enterprises with a robust, easily deployable tool that is both versatile in its application and proactive in its defense approach, ensuring that networks remain resilient against the continuously evolving spectrum of cyber threats.

# Notebooks can be loaded and run through the google colab services.

For the process flow chart, Figure 1 shows the CICIDS 2017 dataset, data preparation, data normalisation, partitioning into 80% and 20%, the iterative steps through the deep layers, and the resulting predictions for each cyber-attack category. Moreover, metrics concerning classification outcomes and ROC curves are calculated for each attack category. The neural network model comprises three deep layers. The first layer comprises of 130 neurons running on a RELU activation function. The following layer has 83 neurons with RELU activation. Finally, the third layer consists of 78 neurons employing a Softmax activation function. These elements generate the output predictions as shown in table 3 of the hyperparameters.

![proceso](https://github.com/fabian692/redes-neuronales-tesis/assets/57039323/057be3e5-d31b-44bc-97b9-953dfb2acb8d)

The convolutional neural network model is structured with a 100-unit 2D convolutional layer. Its kernel size is (1,10) and its strides are (1,1). After this layer, there is a MaxPooling2D layer with a pool size of (1,2), a flattening layer, and 2 hidden layers. The initial layer has 80 neurons with a RELU activation function, while the second layer has 78 neurons with a Softmax activation function.

![red conv](https://github.com/fabian692/redes-neuronales-tesis/assets/57039323/599285bc-51cc-4e2c-9491-294064cb2a69)


