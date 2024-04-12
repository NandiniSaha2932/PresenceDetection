<h1>Presence or Absence Detection of St. George in an image</h1>
<h2>Summary of the Project</h2>
<ul>
  <li><p>Introduction</p></li>
  <p>In this study, we develop a method for identifying images that depict St. George by employing a neural network. Our approach uses a compiled dataset of images, categorized into those that feature St. George and those that do not. This document outlines the selection of the neural network model, the metrics used to assess its performance, and the findings from our experiments. Moreover, it describes a function designed to input an image and determine whether it contains an image of St. George.</p>
  <li><p>Used Model</p></li>
  <p>For this project, we opted to use the VGG16 architecture due to its proven track record in handling image classification challenges. VGG16 is a pre-trained, deep convolutional neural network model originally developed and trained on the extensive ImageNet dataset. It features 16 layers, including 13 convolutional layers followed by 3 fully connected layers, and is celebrated for its straightforward structure yet powerful performance in classifying images. This model's effectiveness and robustness in various visual recognition scenarios make it an excellent choice for detecting the presence of St. George in images.</p>
  <li><p>Evaluation Metrices</p></li>
  <p>For assessing the performance of the model in identifying St. George in images, we employed several key evaluation metrics. Accuracy measures the proportion of correct predictions out of all predictions made. Precision quantifies the fraction of true positive results among all positive predictions made by the model. Recall evaluates the fraction of true positives identified out of all actual positives present in the dataset. The F1 Score is computed as the harmonic mean of Precision and Recall, providing a balance between the two. These metrics were selected to comprehensively measure the model's effectiveness in this specific image classification task.</p>
  <li><p>Result</p></li>
  <p>The dataset used to train the model included 2680 images featuring St. George and 3366 images that did not contain St. George. Upon training, the model attained an accuracy rate of 85%. This high level of accuracy demonstrates the model's robust capability to accurately distinguish images that depict St. George from those that do not.</p>
  <li><p>Conclusion</p></li>
  <p>In this initiative, we constructed a classifier to identify images containing St. George using the VGG16 architecture, a pre-trained convolutional neural network known for its efficacy in numerous image classification scenarios. We adapted the model to our specific needs by locking the pre-trained layers' weights and introducing additional layers—specifically, new hidden layers with 256 units each and a final binary output layer (one unit for St. George, one for the absence thereof). To prevent overfitting, a Dropout layer was incorporated into the architecture.</p>
</ul>

<h3>The Final Result</h3>
The Final Result is <a style ="text-decoration:none" href = "https://drive.google.com/file/d/1TDsvB2lclmij514uWbdmE2FcW6uEgMAL/view?usp=sharing"> click here 👈</a>
