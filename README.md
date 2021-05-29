# Detecting Depression And Suicidal Possibility With A Person With Deep Learning
<img src="https://resize.indiatvnews.com/en/resize/newbucket/1200_-/2019/08/suicide-1565847830.jpg" width="950" height="520">
<p>Depression is one of the most common mental illnesses in the world, WHO estimates that more than 300 million people worldwide suffer from depression. Depression is also a leading reason behind people commenting suicide. To tackle this problem and prevent it from happening here I have created a Natura Language System powered by Deep Learning that identifies depression and the suicidal chance for a person.</p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
  <li>Spacy</li>
  <li>BeautifulSoup</li>
  <li>Wordcloud</li>
</ul>
<h2>Word Cloud Representation</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Determining-Depression-And-Suicidal-Possibility-With-A-Person/blob/main/Graphs%20%26%20Pictures/word_cloud.png" alt="wordcloud" >
</p> 
<h2>Target Class Distribution</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Determining-Depression-And-Suicidal-Possibility-With-A-Person/blob/main/Graphs%20%26%20Pictures/Distribution%20Of%20Target%20Variable.png" >
</p> 
<p align="center">
<img src="https://github.com/NavinBondade/Determining-Depression-And-Suicidal-Possibility-With-A-Person/blob/main/Graphs%20%26%20Pictures/Distribution%20Of%20Target%20Variable%20In%20Percentage.png">
</p> 
<h2>Model Details</h2>
<p>For the identification of depression and suidewatch within the text, I have created a deep learning model that uses convolution and fully connected neural network layers. The model uses two layers of one dimension convolutional neural networks for feature extraction and three fully connected neural network layers for decision making.  All the layers use RELU as an activation function except the last dense layer that uses the softmax activation function.</p>
<h2>Model Traning</h2>
<p>The model has trained for 150 epochs. During training, the model uses Stochastic Gradient Descent as an optimizer and uses categorical
cross-entropy as the loss function to penalize the model more when it makes a false prediction.</p>
<h2>Model Analysis</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Determining-Depression-And-Suicidal-Possibility-With-A-Person/blob/main/Graphs%20%26%20Pictures/Loss.png">
</p> 
<p align="center">
<img src="https://github.com/NavinBondade/Determining-Depression-And-Suicidal-Possibility-With-A-Person/blob/main/Graphs%20%26%20Pictures/Accuracy.png">
</p> 
<ul>
  <li><b>Accuracy Train Data: 86%</b></li>
  <li><b>Loss Train Data: 0.32</b></li> 
  <li><b>Accuracy Test Data: 76%</b></li>
  <li><b>Loss Test Data: 0.57</b></li>
</ul>
<h2>Conclusion</h2>
<p>Here in this project I have created a Natura Language System powered by Deep Learning that identifies depression and the suicidal chance for a person.</p>
