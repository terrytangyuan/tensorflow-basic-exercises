# CCASA 2017 TensorFlow Exercise

# Exercise 1: Minimize error using cross entropy

**Hint a:** Definition of [cross entropy](https://en.wikipedia.org/wiki/Cross_entropy) on Wikipedia. 
**Hint b:** you'll need to use `tf.reduce_mean`, `tf.reduce_sum`, and `tf.log`.

# Exercise 2: Exponential decay learning rate

**Hint a:** API Documentation for [Exponential Decay](https://www.tensorflow.org/api_docs/python/tf/train/exponential_decay). 
**Hint b:** you can use `global_step = tf.Variable(0, trainable=False)` to initialize global step.

Exercise 3: Achieve higher accuracy as much as possible (minimum 0.93)

**Hint:** tune learning_rate, change optimizers, change cost function, more training steps, early stoping, etc.
