This is a set of notes on online class [Introduction to TensorFlow for Artificial Intelligence](https://www.coursera.org/learn/introduction-tensorflow/home/welcome)

class src https://github.com/lmoroney/dlaicourse 
[colab copy src](https://colab.research.google.com/github/lmoroney/dlaicourse/blob/master/)

Google hosted Jupiter notepad - **Colab** tool info https://colab.research.google.com/notebooks/welcome.ipynb

Fully connected NN (FNN) basic linear algebra and back propagation [NN Overview by NG](https://youtu.be/fXOsFF95ifk).

[Convolution NN (CNN) algebra by NG](https://www.youtube.com/playlist?list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF)
[convolution filters](https://lodev.org/cgtutor/filtering.html) like blur, sharpen, edges.

[Understanding Categorical Cross-Entropy Loss 2018](https://gombru.github.io/2018/05/23/cross_entropy_loss/)
</br> 
**Cross-Entropy loss** </br>
**Logistic Loss** and Multinomial Logistic Loss are other names for Cross-Entropy loss. TensorFlow: [log_loss](https://www.tensorflow.org/api_docs/python/tf/losses/log_loss). *Logistig regression* = binary classification problem.
</br> 
**Categorical Cross-Entropy loss**</br>
Is limited to multi-class classification.
TensorFlow: [softmax_cross_entropy](https://www.tensorflow.org/api_docs/python/tf/losses/softmax_cross_entropy),  sparse_softmax_cross_entropy.
</br> 
**Binary Cross-Entropy Loss**</br> 
It is a Sigmoid activation plus a Cross-Entropy loss. Unlike Softmax loss it is independent for each vector component (class), meaning that the loss computed for every CNN output vector component is not affected by other component values. [TF.sigmoid_cross_entropy_with_logits]()
</br> 
**Focal Loss**</br> 
Focal loss is a Cross-Entropy Loss that weighs the contribution of each sample to the loss based in the classification error. The idea is that, if a sample is already classified correctly by the CNN, its contribution to the loss decreases.
</br> 
[Binary Classification by NG](https://www.youtube.com/watch?v=eqEc66RFY0I)
[Logistic Regression by NG](https://youtu.be/hjrYrynGWGA)

