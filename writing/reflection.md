## Names: Orion Grieco and Renee Tetlow

### Performance

Did the network's output make sense?
The output did not make much sense with the initial weights. The neural network did not predict the dog would bark unless the dog was very tired, or it had been at least 6 hours since the dog's last meal (with favorable other inputs as well). Thus, the neural network (with the original weights) tends to underpredict when the dog will bark.

How could you adjust weights or activation functions to improve accuracy?
One way to improve accuracy would be to increase the weights for the first two neurons (hours since last meal and hours since last time exercising). One could also consider reducing the weight for tiredness (or even making the weight slightly negative). Another possible solution is to increase the bias or lower the threshold value. This would make the neural network more likely to predict that the dog will bark, fixing the network's underpredicting tendency.

What did you notice about how small changes (e.g., weights) affect outcomes?
Changing the weights had big impacts on when the network would predict the dog would bark. Just changing the weights to 0.5, 0.3, and -0.1 respectively made the neural network much more effective.

### Ethics

What potential biases or ethical considerations could arise in your example scenario?

### Reflection

What was easy to understand about the neural network?
What challenges did they face?
