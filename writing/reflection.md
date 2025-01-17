## Names: Orion Grieco and Renee Tetlow

### Performance

Did the network's output make sense?
The output did not make much sense with the initial weights. The neural network did not predict the dog would bark unless the dog was very tired, or it had been at 
least 6 hours since the dog's last meal (with favorable other inputs as well). Thus, the neural network (with the original weights) tends to underpredict when the 
dog will bark.

How could you adjust weights or activation functions to improve accuracy?
One way to improve accuracy would be to increase the weights for the first two neurons (hours since last meal and hours since last time exercising). One could also 
consider reducing the weight for tiredness (or even making the weight slightly negative). Another possible solution is to increase the bias or lower the threshold 
value. This would make the neural network more likely to predict that the dog will bark, fixing the network's underpredicting tendency.

What did you notice about how small changes (e.g., weights) affect outcomes?
Changing the weights had big impacts on when the network would predict the dog would bark. Just changing the weights to 0.5, 0.3, and -0.1 respectively made the 
neural network much more effective.

### Ethics

What potential biases or ethical considerations could arise in your example scenario?
 - Potential violations of ethics might involve restrictions implied by only having three features used to calculate the output. Dogs have further needs beyond being fed or engaging in physical exercise; they require affection of some sort (being catered to, petting, getting a new toy, etc.). Also, there are a multude of different species of dog(s) that may be presidposed to bark on a higher frequency. For example, breeds intented to be hunting dogs may instinctually bark more on average due to that being the primary way of notifying their respective owner of the presence of a fox, fowl, or any other relevant animal that would be hunted.

### Reflection

What was easy to understand about the neural network?
  - The most understandable portions of the neural network was the structure. The single layer of neurons kept the system simple, and did not create any complications in the calulation(s) of the output. This further kept the neural network simple in nature, allowing for an easier comprehension of how the neuron affected the outcome. The anology of using dogs in the model of the neural network also helped with developing a better understanding of how each feature within our single neuron worked together in the calculation of the final outcome of if the dog would or would not bark.

What challenges did they face?
One of the challenges we faced was deciding what structure to use for our neural network. We decided on one neuron for simplicity's sake. Also, our initial weights
had to be changed in order to improve the accuracy of the network. Additionally, we did not know whether a weight could be negative or not until we googled it.
