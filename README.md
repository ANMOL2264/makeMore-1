# Create New Names/Text

This project leverages a simple neural network to generate new names by training on a large dataset of existing names.  

## Approach  
To achieve this, we use **bigrams**. Each bigram provides the probability of the next character occurring based on the preceding character. This approach allows us to create a model that adjusts the probabilities with appropriate weights, ultimately generating new, meaningful names.  

## Explanation  
The project includes detailed comments and markdown to explain the code, especially to aid future reference.  

This project demonstrates the inner workings of a neural network by using **loss** and **probabilities** as the driving factors to determine the next character. **Gradient descent** is employed to minimize the loss.  

The core functionality focuses on maximizing the **likelihood** of the next character based on the training data and the occurrence patterns of bigrams for the given initial character.  

Additionally, the model determines the **starting** and **ending** characters using the same underlying principles.  
