# Zero to Mastery Deep Learning with TensorFlow
All of the course materials for the [Zero to Mastery Deep Learning with TensorFlow course](https://dbourke.link/ZTMTFcourse).

This course will teach you foundations of deep learning and TensorFlow as well as prepare you to pass the TensorFlow Developer Certification exam (optional).

Before signing up to the full course, you can watch the first 14-hours of videos on YouTube in a two part series:
* [Part 1](https://youtu.be/tpCFfeUEGs8) contains notebooks 00, 01 and some of 02 (see below)
* [Part 2](https://youtu.be/ZUKz4125WNI) starts where part 1 left off and finishes the rest of 02

Otherwise, enjoy the contents of this page:
- [Course materials](https://github.com/mrdbourke/tensorflow-deep-learning#course-materials) (everything you'll need for completing the course)
- [Course structure](https://github.com/mrdbourke/tensorflow-deep-learning#course-structure) (how this course is taught)
- [Should you do this course?](https://github.com/mrdbourke/tensorflow-deep-learning#should-you-do-this-course) (decide by answering a couple simple questions)
- [Prerequisites](https://github.com/mrdbourke/tensorflow-deep-learning#prerequisites) (what skills you'll need to do this course)
- [Exercises & Extra-curriculum](https://github.com/mrdbourke/tensorflow-deep-learning#-exercises---extra-curriculum) (challenges to practice what you've learned and resources to learn more)
- [Ask a question](https://github.com/mrdbourke/tensorflow-deep-learning#ask-questions) (like to know more? go here)
- [Status/TODO](https://github.com/mrdbourke/tensorflow-deep-learning#status) (there's still more to come!)
- [Log](https://github.com/mrdbourke/tensorflow-deep-learning#log) (updates, changes and progress)

## Course materials

This table is the ground truth for course materials. All the links you need for everything will be here.

Key:
* **Number:** The number of the target notebook (this may not match the video section of the course but it ties together all of the materials in the table)
* **Notebook:** The notebook for a particular module with lots of code and text annotations (notebooks from the videos are based on these)
* **Data/model:** Links to datasets/pre-trained models for the assosciated notebook
* **Exercises & Extra-curriculum:** Each module comes with a set of exercises and extra-curriculum to help practice your skills and learn more, I suggest going through these **before** you move onto the next module
* **Slides:** Although we focus on writing TensorFlow code, we sometimes use pretty slides to describe different concepts, you'll find them here

**Note:** You can get all of the notebook code created during the videos in the [`video_notebooks`](https://github.com/mrdbourke/tensorflow-deep-learning/tree/main/video_notebooks) directory.

| Number | Notebook | Data/Model | Exercises & Extra-curriculum | Slides |
| ----- |  ----- |  ----- |  ----- |  ----- |
| 00 | [TensorFlow Fundamentals](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/00_tensorflow_fundamentals.ipynb) |  | [Go to exercises & extra-curriculum](https://github.com/mrdbourke/tensorflow-deep-learning#-00-tensorflow-fundamentals-exercises) | [Go to slides](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/slides/00_introduction_to_tensorflow_and_deep_learning.pdf) |
| 01 | [TensorFlow Regression](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/01_neural_network_regression_in_tensorflow.ipynb) |  | [Go to exercises & extra-curriculum](https://github.com/mrdbourke/tensorflow-deep-learning#-01-neural-network-regression-with-tensorflow-exercises) | [Go to slides](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/slides/01_neural_network_regression_with_tensorflow.pdf) |
| 02 | [TensorFlow Classification](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/02_neural_network_classification_in_tensorflow.ipynb) |  | [Go to exercises & extra-curriculum](https://github.com/mrdbourke/tensorflow-deep-learning#-02-neural-network-classification-with-tensorflow-exercises) | [Go to slides](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/slides/02_neural_network_classification_with_tensorflow.pdf) |
| 03 | [TensorFlow Computer Vision](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/03_convolutional_neural_networks_in_tensorflow.ipynb) | [`pizza_steak`](https://storage.googleapis.com/ztm_tf_course/food_vision/pizza_steak.zip), [`10_food_classes_all_data`](https://storage.googleapis.com/ztm_tf_course/food_vision/10_food_classes_all_data.zip) | [Go to exercises & extra-curriculum](https://github.com/mrdbourke/tensorflow-deep-learning#-03-computer-vision--convolutional-neural-networks-in-tensorflow-exercises) | [Go to slides](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/slides/03_convolution_neural_networks_and_computer_vision_with_tensorflow.pdf) |
| 04 | [Transfer Learning Part 1: Feature extraction](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/04_transfer_learning_in_tensorflow_part_1_feature_extraction.ipynb) | [`10_food_classes_10_percent`](https://storage.googleapis.com/ztm_tf_course/food_vision/10_food_classes_10_percent.zip) | [Go to exercises & extra-curriculum](https://github.com/mrdbourke/tensorflow-deep-learning#-04-transfer-learning-in-tensorflow-part-1-feature-extraction-exercises) | [Go to slides](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/slides/04_transfer_learning_with_tensorflow_part_1_feature_extraction.pdf) |
| 05 | [Transfer Learning Part 2: Fine-tuning](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/05_transfer_learning_in_tensorflow_part_2_fine_tuning.ipynb) | [`10_food_classes_10_percent`](https://storage.googleapis.com/ztm_tf_course/food_vision/10_food_classes_10_percent.zip), [`10_food_classes_1_percent`](https://storage.googleapis.com/ztm_tf_course/food_vision/10_food_classes_1_percent.zip), [`10_food_classes_all_data`](https://storage.googleapis.com/ztm_tf_course/food_vision/10_food_classes_all_data.zip) | [Go to exercises & extra-curriculum](https://github.com/mrdbourke/tensorflow-deep-learning#-05-transfer-learning-in-tensorflow-part-2-fine-tuning-exercises) | [Go to slides](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/slides/05_transfer_learning_with_tensorflow_part_2_fine_tuning.pdf) |
| 06 | [Transfer Learning Part 3: Scaling up](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/06_transfer_learning_in_tensorflow_part_3_scaling_up.ipynb) | [`101_food_classes_10_percent`](https://storage.googleapis.com/ztm_tf_course/food_vision/101_food_classes_10_percent.zip), [`custom_food_images`](https://storage.googleapis.com/ztm_tf_course/food_vision/custom_food_images.zip), [`fine_tuned_efficientnet_model`](https://storage.googleapis.com/ztm_tf_course/food_vision/06_101_food_class_10_percent_saved_big_dog_model.zip) | [Go to exercises & extra-curriculum](https://github.com/mrdbourke/tensorflow-deep-learning#-06-transfer-learning-in-tensorflow-part-3-scaling-up-exercises) | [Go to slides](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/slides/06_transfer_learning_with_tensorflow_part_3_scaling_up.pdf) |
| 07 | Milestone project 1: Food Vision (coming soon) |  | |  |
| 08 | TensorFlow NLP Fundamentals (coming soon) |  |  |  |
| 09 | Milestone project 2: SkimLit (coming soon) |  |  |  |
| 10 | TensorFlow Time Series Fundamentals & Milestone project 3 (coming soon) | | | |

## Course structure

This course is code first. The goal is to get you writing deep learning code as soon as possible.

It is taught with the following mantra:

```
Code -> Concept -> Code -> Concept -> Code -> Concept
```

This means we write code first then step through the concepts behind it.

If you've got 6-months experience writing Python code and a willingness to learn (most important), you'll be able to do the course.

## Should you do this course?

> Do you have 1+ years experience with deep learning and writing TensorFlow code?

If yes, no you shouldn't, use your skills to build something. 

If no, move onto the next question.

> Have you done at least one beginner machine learning course and would like to learn about deep learning/pass the TensorFlow Developer Certification?

If yes, this course is for you.

If no, go and do a beginner machine learning course and if you decide you want to learn TensorFlow, this page will still be here.

## Prerequisites

> What do I need to know to go through this course?

* **6+ months writing Python code.** Can you write a Python function which accepts and uses parameters? That’s good enough. If you don’t know what that means, spend another month or two writing Python code and then come back here.
* **At least one beginner machine learning course.** Are you familiar with the idea of training, validation and test sets? Do you know what supervised learning is? Have you used pandas, NumPy or Matplotlib before? If no to any of these, I’d going through at least one machine learning course which teaches these first and then coming back. 
* **Comfortable using Google Colab/Jupyter Notebooks.** This course uses Google Colab throughout. If you have never used Google Colab before, it works very similar to Jupyter Notebooks with a few extra features. If you’re not familiar with Google Colab notebooks, I’d suggest going through the Introduction to Google Colab notebook.
* **Plug:** The [Zero to Mastery beginner-friendly machine learning course](https://dbourke.link/ZTMMLcourse) (I also teach this) teaches all of the above (and this course is designed as a follow on).

## 🛠 Exercises & 📖 Extra-curriculum

To prevent the course from being 100+ hours (deep learning is a broad field), various external resources for different sections are recommended to puruse under your own discrestion.

(solutions to come after the course is released... try the exercises out for yourself first!)

---

### 🛠 00 TensorFlow Fundamentals Exercises

1. Create a vector, scalar, matrix and tensor with values of your choosing using `tf.constant()`.
2. Find the shape, rank and size of the tensors you created in 1.
3. Create two tensors containing random values between 0 and 1 with shape `[5, 300]`.
4. Multiply the two tensors you created in 3 using matrix multiplication.
5. Multiply the two tensors you created in 3 using dot product.
6. Create a tensor with random values between 0 and 1 with shape `[224, 224, 3]`.
7. Find the min and max values of the tensor you created in 6.
8. Created a tensor with random values of shape `[1, 224, 224, 3]` then squeeze it to change the shape to `[224, 224, 3]`.
9. Create a tensor with shape `[10]` using your own choice of values, then find the index which has the maximum value.
10. One-hot encode the tensor you created in 9.

### 📖 00 TensorFlow Fundamentals Extra-curriculum 

* Read through the [list of TensorFlow Python APIs](https://www.tensorflow.org/api_docs/python/), pick one we haven't gone through in this notebook, reverse engineer it (write out the documentation code for yourself) and figure out what it does.
* Try to create a series of tensor functions to calculate your most recent grocery bill (it's okay if you don't use the names of the items, just the price in numerical form).
  * How would you calculate your grocery bill for the month and for the year using tensors?
* Go through the [TensorFlow 2.x quick start for beginners](https://www.tensorflow.org/tutorials/quickstart/beginner) tutorial (be sure to type out all of the code yourself, even if you don't understand it).
  * Are there any functions we used in here that match what's used in there? Which are the same? Which haven't you seen before?
* Watch the video ["What's a tensor?"](https://www.youtube.com/watch?v=f5liqUk0ZTw) - a great visual introduction to many of the concepts we've covered in this notebook.

---

### 🛠 01 Neural network regression with TensorFlow Exercises

1. Create your own regression dataset (or make the one we created in "Create data to view and fit" bigger) and build fit a model to it.
2. Try building a neural network with 4 Dense layers and fitting it to your own regression dataset, how does it perform?
3. Try and improve the results we got on the insurance dataset, some things you might want to try include:
  * Building a larger model (how does one with 4 dense layers go?).
  * Increasing the number of units in each layer.
  * Lookup the documentation of [Adam](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/Adam) and find out what the first parameter is, what happens if you increase it by 10x?
  * What happens if you train for longer (say 300 epochs instead of 200)? 
4. Import the [Boston pricing dataset](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/boston_housing/load_data) from TensorFlow [`tf.keras.datasets`](https://www.tensorflow.org/api_docs/python/tf/keras/datasets) and model it.

### 📖 01 Neural network regression with TensorFlow Extra-curriculum

* [MIT introduction deep learning lecture 1](https://youtu.be/njKP3FqW3Sk) - gives a great overview of what's happening behind all of the code we're running.
* Reading: 1-hour of [Chapter 1 of Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/chap1.html) by Michael Nielson - a great in-depth and hands-on example of the intuition behind neural networks.
* To practice your regression modelling with TensorFlow, I'd also encourage you to look through [Lion Bridge's collection of datasets](https://lionbridge.ai/datasets/) or [Kaggle's datasets](https://www.kaggle.com/data), find a regression dataset which sparks your interest and try to model.

---

### 🛠 02 Neural network classification with TensorFlow Exercises

1. Play with neural networks in the [TensorFlow Playground](https://playground.tensorflow.org/) for 10-minutes. Especially try different values of the learning, what happens when you decrease it? What happens when you increase it?
2. Replicate the model pictured in the [TensorFlow Playground diagram](https://playground.tensorflow.org/#activation=relu&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.001&regularizationRate=0&noise=0&networkShape=6,6,6,6,6&seed=0.51287&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false&regularization_hide=true&discretize_hide=true&regularizationRate_hide=true&percTrainData_hide=true&dataset_hide=true&problem_hide=true&noise_hide=true&batchSize_hide=true) below using TensorFlow code. Compile it using the Adam optimizer, binary crossentropy loss and accuracy metric. Once it's compiled check a summary of the model.
![tensorflow playground example neural network](https://raw.githubusercontent.com/mrdbourke/tensorflow-deep-learning/main/images/02-tensorflow-playground-replication-exercise.png)
*Try this network out for yourself on the [TensorFlow Playground website](https://playground.tensorflow.org/#activation=relu&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.001&regularizationRate=0&noise=0&networkShape=6,6,6,6,6&seed=0.51287&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false&regularization_hide=true&discretize_hide=true&regularizationRate_hide=true&percTrainData_hide=true&dataset_hide=true&problem_hide=true&noise_hide=true&batchSize_hide=true). Hint: there are 5 hidden layers but the output layer isn't pictured, you'll have to decide what the output layer should be based on the input data.*
3. Create a classification dataset using Scikit-Learn's [`make_moons()`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_moons.html) function, visualize it and then build a model to fit it at over 85% accuracy.
4. Create a function (or write code) to visualize multiple image predictions for the fashion MNIST at the same time. Plot at least three different images and their prediciton labels at the same time. Hint: see the [classifcation tutorial in the TensorFlow documentation](https://www.tensorflow.org/tutorials/keras/classification) for ideas.
5. Recreate [TensorFlow's](https://www.tensorflow.org/api_docs/python/tf/keras/activations/softmax) [softmax activation function](https://en.wikipedia.org/wiki/Softmax_function) in your own code. Make sure it can accept a tensor and return that tensor after having the softmax function applied to it.
6. Train a model to get 88%+ accuracy on the fashion MNIST test set. Plot a confusion matrix to see the results after.
7. Make a function to show an image of a certain class of the fashion MNIST dataset and make a prediction on it. For example, plot 3 images of the `T-shirt` class with their predictions.

### 📖 02 Neural network classification with TensorFlow Extra-curriculum

* Watch 3Blue1Brown's neural networks video 2: [*Gradient descent, how neural networks learn*](https://www.youtube.com/watch?v=IHZwWFHWa-w). After you're done, write 100 words about what you've learned.
  * If you haven't already, watch video 1: [*But what is a Neural Network?*](https://youtu.be/aircAruvnKk). Note the activation function they talk about at the end.
* Watch [MIT's introduction to deep learning lecture 1](https://youtu.be/njKP3FqW3Sk) (if you haven't already) to get an idea of the concepts behind using linear and non-linear functions.
* Spend 1-hour reading [Michael Nielsen's Neural Networks and Deep Learning book](http://neuralnetworksanddeeplearning.com/index.html).
* Read the [ML-Glossary documentation on activation functions](https://ml-cheatsheet.readthedocs.io/en/latest/activation_functions.html). Which one is your favourite?
  * After you've read the ML-Glossary, see which activation functions are available in TensorFlow by searching "tensorflow activation functions".

---

### 🛠 03 Computer vision & convolutional neural networks in TensorFlow Exercises

1. Spend 20-minutes reading and interacting with the [CNN explainer website](https://poloclub.github.io/cnn-explainer/). 
 * What are the key terms? e.g. explain convolution in your own words, pooling in your own words
2. Play around with the "understanding hyperparameters" section in the [CNN explainer](https://poloclub.github.io/cnn-explainer/) website for 10-minutes.
  * What is the kernel size?
  * What is the stride? 
  * How could you adjust each of these in TensorFlow code?
3. Take 10 photos of two different things and build your own CNN image classifier using the techniques we've built here.
4. Find an ideal learning rate for a simple convolutional neural network model on your the 10 class dataset.

### 📖 03 Computer vision & convolutional neural networks in TensorFlow Extra-curriculum

* **Watch:** [MIT's Introduction to Deep Computer Vision](https://www.youtube.com/watch?v=iaSUYvmCekI&list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI&index=3) lecture. This will give you a great intuition behind convolutional neural networks.
* **Watch:** Deep dive on [mini-batch gradient descent](https://youtu.be/-_4Zi8fCZO4) by deeplearning.ai. If you're still curious about why we use **batches** to train models, this technical overview covers many of the reasons why.
* **Read:** [CS231n Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/convolutional-networks/) class notes. This will give a very deep understanding of what's going on behind the scenes of the convolutional neural network architectures we're writing. 
* **Read:** ["A guide to convolution arithmetic for deep learning"](https://arxiv.org/pdf/1603.07285.pdf). This paper goes through all of the mathematics running behind the scenes of our convolutional layers.
* **Code practice:** [TensorFlow Data Augmentation Tutorial](https://www.tensorflow.org/tutorials/images/data_augmentation). For a more in-depth introduction on data augmentation with TensorFlow, spend an hour or two reading through this tutorial.

---

### 🛠 04 Transfer Learning in TensorFlow Part 1: Feature Extraction Exercises

1. Build and fit a model using the same data we have here but with the MobileNetV2 architecture feature extraction ([`mobilenet_v2_100_224/feature_vector`](https://tfhub.dev/google/imagenet/mobilenet_v2_100_224/feature_vector/4)) from TensorFlow Hub, how does it perform compared to our other models?
2. Name 3 different image classification models on TensorFlow Hub that we haven't used.
3. Build a model to classify images of two different things you've taken photos of.
  * You can use any feature extraction layer from TensorFlow Hub you like for this.
  * You should aim to have at least 10 images of each class, for example to build a fridge versus oven classifier, you'll want 10 images of fridges and 10 images of ovens.
4. What is the current best performing model on ImageNet?
  * Hint: you might want to check [sotabench.com](https://www.sotabench.com) for this.

### 📖 04 Transfer Learning in TensorFlow Part 1: Feature Extraction Extra-curriculum

* Read through the [TensorFlow Transfer Learning Guide](https://www.tensorflow.org/tutorials/images/transfer_learning) and define the main two types of transfer learning in your own words.
* Go through the [Transfer Learning with TensorFlow Hub tutorial](https://www.tensorflow.org/tutorials/images/transfer_learning_with_hub) on the TensorFlow website and rewrite all of the code yourself into a new Google Colab notebook making comments about what each step does along the way.
* We haven't covered fine-tuning with TensorFlow Hub in this notebook, but if you'd like to know more, go through the [fine-tuning a TensorFlow Hub model tutorial](https://www.tensorflow.org/hub/tf2_saved_model#fine-tuning) on the TensorFlow homepage.How to fine-tune a tensorflow hub model:  
* Look into [experiment tracking with Weights & Biases](https://www.wandb.com/experiment-tracking), how could you integrate it with our existing TensorBoard logs?

---

### 🛠 05 Transfer Learning in TensorFlow Part 2: Fine-tuning Exercises

1. Write a function to visualize an image from any dataset (train or test file) and any class (e.g. "steak", "pizza"... etc), visualize it and make a prediction on it using a trained model.
2. Use feature-extraction to train a transfer learning model on 10% of the Food Vision data for 10 epochs using [`tf.keras.applications.EfficientNetB0`](https://www.tensorflow.org/api_docs/python/tf/keras/applications/EfficientNetB0) as the base model. Use the [`ModelCheckpoint`](https://www.tensorflow.org/api_docs/python/tf/keras/callbacks/ModelCheckpoint) callback to save the weights to file.
3. Fine-tune the last 20 layers of the base model you trained in 2 for another 10 epochs. How did it go?
4. Fine-tune the last 30 layers of the base model you trained in 2 for another 10 epochs. How did it go?

### 📖 05 Transfer Learning in TensorFlow Part 2: Fine-tuning Extra-curriculum

* Read the [documentation on data augmentation](https://www.tensorflow.org/tutorials/images/data_augmentation) in TensorFlow.
* Read the [ULMFit paper](https://arxiv.org/abs/1801.06146) (technical) for an introduction to the concept of freezing and unfreezing different layers.
* Read up on learning rate scheduling (there's a [TensorFlow callback](https://www.tensorflow.org/api_docs/python/tf/keras/callbacks/LearningRateScheduler) for this), how could this influence our model training?
  * If you're training for longer, you probably want to reduce the learning rate as you go... the closer you get to the bottom of the hill, the smaller steps you want to take. Imagine it like finding a coin at the bottom of your couch. In the beginning your arm movements are going to be large and the closer you get, the smaller your movements become.
  
---

### 🛠 06 Transfer Learning in TensorFlow Part 3: Scaling-up Exercises

1. Take 3 of your own photos of food and use the trained model to make predictions on them, share your predictions with the other students in Discord and show off your Food Vision model 🍔👁.
2. Train a feature-extraction transfer learning model for 10 epochs on the same data and compare its performance versus a model which used feature extraction for 5 epochs and fine-tuning for 5 epochs (like we've used in this notebook). Which method is better?
3. Recreate the first model (the feature extraction model) with [`mixed_precision`](https://www.tensorflow.org/guide/mixed_precision) turned on. 
  * Does it make the model train faster? 
  * Does it effect the accuracy or performance of our model? 
  * What's the advatanges of using `mixed_precision` training?

### 📖 06 Transfer Learning in TensorFlow Part 3: Scaling-up Extra-curriculum
* Spend 15-minutes reading up on the [EarlyStopping callback](https://www.tensorflow.org/api_docs/python/tf/keras/callbacks/EarlyStopping). What does it do? How could we use it in our model training?
* Spend an hour reading about [Streamlit](https://www.streamlit.io/). What does it do? How might you integrate some of the things we've done in this notebook in a Streamlit app?

---

## What this course is missing

Deep learning is a broad topic. So this course doesn't cover it all. 

Here are some of the main topics you might want to look into next:

* Transformers (the neural network architecture taking the NLP world by storm)
* Multi-modal models (models which use more than one data source such as text & images)
* Reinforcement learning
* Unsupervised learning

## Ask questions

Contact [Daniel Bourke](mailto:daniel@mrdbourke.com) or [add a discussion](https://github.com/mrdbourke/tensorflow-deep-learning/discussions) (preferred).

# Status

As of: 17 Mar 2021 - LAUNCHED! 

* **Currently:** Preparing slides & notebook for 07 (livestreaming lots of this on Twitch: https://www.twitch.tv/mrdbourke)
* **Video count:** 182/~220+, aiming to do ~10 videos per day during recording sessions
* Finished videos for: 00, 01, 02, 03, 04, 05, 06
* Finished slides for notebooks: 00, 01, 02, 03, 04, 05, 06
* Polished (prepared them for external use) notebooks: 00, 01, 02, 03, 04, 05, 06
* Finished 09/10 of code notebooks (time series still to come)
* Video studio setup! ([see the makeshift closet studio](https://raw.githubusercontent.com/mrdbourke/tensorflow-deep-learning/main/images/misc-studio-setup.jpeg))
* Created GitHub Project page! See a cool Kanban setup here: https://github.com/mrdbourke/tensorflow-deep-learning/projects/1
* Created GitHub Discussion page! Going to use this for popular QA/course tidbits: https://github.com/mrdbourke/tensorflow-deep-learning/discussions

## TODO
geez... I forgot how much there was still to go... classic project planning

* ✅ Make a GitHub Project for course (see "Projects" tab)
* ✅ Make a [GitHub Discussions](https://github.com/vercel/vercel/discussions/3874) for course (thank you [Alvaro](https://github.com/alvarobartt))
* ✅ Polish GitHub readme (what you're reading now) with extra resources: 
  * data links used in course
  * extra resources & curriculum
* 🔜 Upload slides for each section, done for: 00, 01, 02, 03, 04, 05, 06 (see [course materials](https://github.com/mrdbourke/tensorflow-deep-learning#course-materials))
* 🔜 Upload video notebooks for each section, done for: 00, 01, 02, 03, 04, 05, 06 (see [.video_notebooks/](https://github.com/mrdbourke/tensorflow-deep-learning/tree/main/video_notebooks)) 
* Make Colab overview video (Colab is the tool we'll be using for the whole course)
* Make course resource overview video (e.g. how to use this GitHub, Discussions page, exercises, extra-curriculum etc)
* Upload solutions for exercises (probably livestream the creation of these after course launch)
  
## Log
* 17 Mar 2021 - 99% finished notebook 07, added links to first 14 hours of the course on YouTube ([10 hours in part 1](https://youtu.be/tpCFfeUEGs8), [4 hours in part 2](https://youtu.be/ZUKz4125WNI))
* 11 Mar 2021 - added even more text annotations to notebook 07, finishing tomorrow, then slides
* 10 Mar 2021 - Typed a whole bunch of explanations into notebook 07, continuing tomorrow
* 09 Mar 2021 - fixed plenty of code in notebook 07, should run end to end very cleanly (though loading times are still a thing)
* 05 Mar 2021 - added draft notebook 07 (heaps of data loading and model training improvements in this one!), gonna fix up over next few days
* 01 Mar 2021 - Added slides for 06 ([see them here](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/slides/06_transfer_learning_with_tensorflow_part_3_scaling_up.pdf)) 
* 26 Feb 2021 - 🚀 LAUNCHED!!!!! also finished recording videos for 06, onto 07, 08, 09 for next release 
* 24 Feb 2021 - recorded 9 videos for section 06, launch inbound!!!
* 23 Feb 2021 - rearranged GitHub in preparation for launch 🚀 
* 18 Feb 2021 - recorded 8 videos for 05 and... it's done! onto polishing the GitHub
* 17 Feb 2021 - recorded 10 videos for 05! going to finish tomorrow 🚀
* 16 Feb 2021 - polished slides for 05 and started recording videos, got 7 videos done for 05 
* 15 Feb 2021 - finished videos for 04, now preparing to record for 05!
* 12 Feb 2021 - recored 7 videos for section 04... wanted 10 but we'll take 7 (🤔 this seems to have happened before)
* 11 Feb 2021 - NO PROGRESS - gave a Machine Learning deployment tutorial for [Stanford's CS329s](https://stanford-cs329s.github.io/syllabus.html) (using the model code from this course!!!) - [see the full tutorial materials](https://github.com/mrdbourke/cs329s-ml-deployment-tutorial)
* 08 Feb 2021 - recorded 10 videos for section 03... and section 03 is done! 🚀 onto section 04
* 30 Jan 2021 - 07 Feb 2021: NO PROGRESS (working on a ML deployment lecture for [Stanford's CS329s](https://stanford-cs329s.github.io/syllabus.html)... more on this later)
* 29 Jan 2021 - recorded 9 videos for section 03... closer to 10 than yesterday but still not there
* 28 Jan 2021 - recorded 7 videos for section 03... wanted 10 but we'll take 7
* 27 Jan 2021 - recorded 10 videos for section 03
* 26 Jan 2021 - polished GitHub README (what you're looking at) with a [nice table](https://github.com/mrdbourke/tensorflow-deep-learning#course-materials)
* 23 Jan 2021 - finished slides of 06
* 22 Jan 2021 - finished review of notebook 06 & started slides of 06
* 21 Jan 2021 - finished slides for 05 & started review of 06
* 20 Jan 2021 - finished notebook 05 & 95% slides for 05
* 19 Jan 2021 - found a storage idea for data during course (use Google Storage in same region as Colab Notebooks, cheapest/fastest)
* 18 Jan 2021 - reviewed notebook 05 & slides for 05
* 17 Jan 2021 - finished notebook 04 & slides for 04
* 16 Jan 2021 - review notebook 04 & made slides for transfer learning
* 13 Jan 2021 - review notebook 03 again & finished slides for 03, BIGGGGG updates to the README, notebook 03 99% done, just need to figure out optimum way to transfer data (e.g. when a student downloads it, where's best to store it in the meantime? Dropbox? S3? ~~GS~~ (too expensive)
* 11 Jan 2021 - reviewed notebook 03, 95% ready for recording, onto slides for 03
* 9 Jan 2021 - I'm back baby! Finished all videos for 02, now onto slides/materials for 03, 04, 05 (then I'll get back in the lab)
* 19 Dec 2020 - ON HOLD (family holiday until Jan 02 2021) 
* 18 Dec 2020 - recorded 75% of videos for 02
* 17 Dec 2020 - recorded 50% of videos for 02
* 16 Dec 2020 - recorded 100% of videos for 01
* 15 Dec 2020 - recorded 90% of videos for 01
* 09 Dec 2020 - finished recording videos for 00
* 08 Dec 2020 - recorded 90% of videos for 00
* 05 Dec 2020 - trialled recording studio for ~6 videos with notebook 00 material
* 04 Dec 2020 - setup [recording studio in closet](https://raw.githubusercontent.com/mrdbourke/tensorflow-deep-learning/main/images/misc-studio-setup.jpeg)
* 03 Dec 2020 - finished notebook 02, finished slides for 02, time to setup recording studio
* 02 Dec 2020 - notebook 02 95% done, slides for 02 90% done
* 01 Dec 2020 - added notebook 02 (90% polished), start preparing slides for 02
* 27 Nov 2020 - polished notebook 01, made slides for notebook 01
* 26 Nov 2020 - polished notebook 00, made slides for notebook 00
