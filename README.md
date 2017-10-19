# TensorFlow Basic Exercises

This repo contains exercises for basic TensorFlow tutorial.


# Software Requirements

You need to have [Python](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installing/) installed. Then install [TensorFlow](https://www.tensorflow.org/) via `pip install tensorflow`. Consult [this page](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/g3doc/get_started/os_setup.md) if you want to customize your setup. 

To test your installation, clone this repo and then run `python demo.py`. No error is expected if installation ws successful. You should expect the following at the end of the output:

```
Optimization Finished!
Accuracy: 0.9256
``` 

# Instruction

The Python script [demo.py](./demo.py) provides a basic example for logistic regression using TensorFlow on MNIST hand-written digit data. All the necessary steps, including data preprocessing, model building, and model evaluation, have been done for you so you can focus on small parts of the program. You are expected to make small modifications to the Python script [demo.py](./demo.py) to achieve the goals of the following exercises to get more familiar with TensorFlow's basics.

# Exercises

## Exercise 1: Minimize error using cross entropy as the cost function

* **Hint a:** Definition of [cross entropy](https://en.wikipedia.org/wiki/Cross_entropy) on Wikipedia. 
* **Hint b:** You'll need to use `tf.reduce_mean`, `tf.reduce_sum`, and `tf.log`.

## Exercise 2: Apply exponential learning rate decay

* **Hint a:** TensorFlow has a built-in function for exponential decay. See API Documentation for this [here](https://www.tensorflow.org/api_docs/python/tf/train/exponential_decay). 
* **Hint b:** You can use `global_step = tf.Variable(0, trainable=False)` to initialize global step.

## Exercise 3: Apply early stopping when a condition is met

* **Hint a:** Calculate the absolute value of the difference between current average cost and previous average cost.
* **Hint b:** When there's no much different, exit the for loop.

## Exercise 4: Apply L1 regularization to weights

* **Hint a:** Definition of [L1 regularization](http://www.chioka.in/differences-between-l1-and-l2-as-loss-function-and-regularization/).
* **Hint b:** Some functions you'll need are: `tf.multiply`, `tf.reduce_sum`, `tf.abs`.
* **Hint c:** Apply this regularization term to when constructing the model.

## Exercise 5: What else can you do to achieve higher accuracy (minimum 0.94)?

* **Hint:** You can tune learning_rate, change optimizers, change initializers, change cost function, more training steps, advanced early stoping, etc. **Be creative!**


# Maintenance

Please contact Yuan Tang (terrytangyuan@gmail.com) if you have any questions or open an issue.

# Credits

Some screenshots are adopted from TensorFlow Dev Summit, TensorFlow paper, and other online resources. Thanks!


 
