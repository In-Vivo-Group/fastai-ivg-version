# Lesson 1: Getting Started, Practical Deep Learning for Coders Part 1

## Course information
- [Lesson 1 page](https://course.fast.ai/Lessons/lesson1.html)
- [Lesson 1 video](https://www.youtube.com/watch?v=8SF_h3xF3cE&t=2s)
- [Lesson 1 notebook](https://www.kaggle.com/code/jhoward/is-it-a-bird-creating-a-model-from-your-own-data)

## Book section to read
- [Book chapter 1](https://colab.research.google.com/github/fastai/fastbook/blob/master/01_intro.ipynb?authuser=3#scrollTo=57tQk0jr1wb6)

## Resources
- [Setting up Kaggle](https://course.fast.ai/Resources/kaggle.html)
- [Links to more resources](https://course.fast.ai/Lessons/lesson1.html#links)
- [fast.ai forums](https://forums.fast.ai/c/p1v5/54)
- [fast.ai datasets](https://docs.fast.ai/data.external.html#datasets)

## Vocabulary
Deep learning vocabulary
|=====
| Term | Meaning
|Label | The data that we're trying to predict, such as "dog" or "cat"
|Architecture | The _template_ of the model that we're trying to fit; the actual mathematical function that we're passing the input data and parameters to
|Model | The combination of the architecture with a particular set of parameters
|Parameters | The values in the model that change what task it can do, and are updated through model training
|Fit | Update the parameters of the model such that the predictions of the model using the input data match the target labels
|Train | A synonym for _fit_
|Pretrained model | A model that has already been trained, generally using a large dataset, and will be fine-tuned
|Fine-tune | Update a pretrained model for a different task
|Epoch | One complete pass through the input data
|Loss | A measure of how good the model is, chosen to drive training via SGD
|Metric | A measurement of how good the model is, using the validation set, chosen for human consumption
|Validation set | A set of data held out from training, used only for measuring how good the model is
|Training set | The data used for fitting the model; does not include any data from the validation set
|Overfitting | Training a model in such a way that it _remembers_ specific features of the input data, rather than generalizing well to data not seen during training
|CNN | Convolutional neural network; a type of neural network that works particularly well for computer vision tasks
|=====