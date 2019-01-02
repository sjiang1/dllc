[//]: # (on odyssey, venv at ~/venv/)

# A TensorFlow and Deep Learning Tutorial for Beginners

This document is for undergrad/master students who are interested in learning deep learning (and TensorFlow) but are not necessarily familiar with machine learning concepts. I will keep updating this document like a small guide and a Q&A site, which are supplementary for [the official TensorFlow Tutorials](https://www.tensorflow.org/tutorials/).

**All questions are welcome!** Including but not limited to:
1. questions about python language
2. questions about machine learning/deep learning
3. questions about Nvidia GPU setup
4. questions about TensorFlow and related libraries

I may not know all the answers but the gist of this document is for us to learn together!

<div style="text-align: right">Siyuan</div>
<div style="text-align: right">01/02/2019</div>

## Prerequisites
This document assumes you know:
1. how to install Python
2. how to run a Python code
3. how to use pip to install packages


## Environment Setup

### Install TensorFlow with pip
[TensorFlow Official Installation Guide](https://www.tensorflow.org/install/pip)

For beginners who currently don't have a GPU, installing TensorFlow for CPU is a good choice. You don't need a GPU to start using TensorFlow. Actually, CPU-only version is recommended for beginners.

For students who have GPU at hand (I hope it's an Nvidia), I recommend the GPU version. [CUDA](https://developer.nvidia.com/cuda-downloads) needs to be installed before the GPU version of TensorFlow. Installing [CUDA](https://developer.nvidia.com/cuda-downloads), [cuDNN](https://developer.nvidia.com/cudnn), is another story (to be told in the future/upon request.) **If you want to install CUDA, make sure to check the CUDA version that TensorFlow supports. For example, the current stable TensorFlow (1.12 version) supports only CUDA 9.0 not CUDA 10.0.**


### PyCharm (optional)
[PyCharm](https://www.jetbrains.com/pycharm/) is a Python IDE offered by [JetBrains](https://www.jetbrains.com). If you just started learning Python, I don't recommend using this IDE (and you can skip this section). But if you are already familiar with Python, this IDE can increase your productivity by highlighting your errors and autocompleting your code. A few extra notes:

1. [JetBrains](https://www.jetbrains.com) offers educational discount. Check out [their educational licenses](https://www.jetbrains.com/student/) and you can access to almost all of their products.
2. [Guide for creating a python project](https://www.jetbrains.com/help/pycharm/creating-empty-project.html)
3. [Guide for configuring the virtualenv environment](https://www.jetbrains.com/help/pycharm/creating-virtual-environment.html)
4. [Guide for switching to **scientific mode**](https://www.jetbrains.com/help/pycharm/matplotlib-support.html#sm)


## Walkthrough the TensorFlow tutorials:
This section will go through each tutorial in [the tutorials in the TensorFlow website](https://www.tensorflow.org/tutorials/). I will keep updating this document like Q&A.

### Tutorial 01: Train your first neural network: basic classification

#### [Tutorial link](https://www.tensorflow.org/tutorials/keras/basic_classification)

##### Note 1: how to show a plot
If you are not familiar with plotting in Python (like me), the following code in this tutorial does not print the plot as expected. (Note that in the tutorial, we already `import matplotlib.pyplot as plt`)

```python
plt.figure()
plt.imshow(train_images[0])
plt.colorbar()
plt.grid(False)
```
The code above just renders the plot but not show the plot. To show the plot, add the following line after the above code:

```python
plt.show()
```

##### Questions
<div style="color: red">For students to add questions here.</div>

### Tutorial 02: Text classification with movie reviews

#### [Tutorial link](https://www.tensorflow.org/tutorials/keras/basic_text_classification)

##### Note 1: every review should start with `<START>` 
In the section "Convert the integers back to words", the first review printed should have `<START>` in the beginning.

##### Questions
<div style="color: red">For students to add questions here.</div>

### Tutorial 03: Regression: predict fuel efficiency

#### [Tutorial link](https://www.tensorflow.org/tutorials/keras/basic_regression)

##### Note 1: to show the plot created by seaborn
`seaborn` is library based on matplotlib. So to show a plot created by seaborn, we need to:
1. import matplotlib.pyplot as plt
2. add plt.show() after seaborn creates a plot

##### Questions
<div style="color: red">For students to add questions here.</div>


