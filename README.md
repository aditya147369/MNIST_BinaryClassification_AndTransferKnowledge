MNIST Binary Classification with Knowledge Transfer
This project uses the MNIST dataset to predict whether a number is even or odd by leveraging pre-trained weights from a model that was initially trained to classify digits 0-9.

I perform knowledge transfer by freezing the weights of the original model and repurposing it for a binary classification task. The steps are:

1. Load the pre-trained model trained on MNIST.

2. Freeze all layers except the final classification layer.

3. Modify the final layer to output a single binary prediction (even or odd).

4. Train the modified model on the MNIST dataset with labels indicating even or odd numbers
