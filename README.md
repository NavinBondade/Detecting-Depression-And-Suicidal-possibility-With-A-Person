# Detecting Depression And Suicidal Possibility With A Person With Deep Learning
<p align="center">
<a href="https://nbviewer.jupyter.org/github/NavinBondade/Determining-Depression-And-Suicidal-Possibility-With-A-Person/blob/main/Notebook/Determining_Whether_A_Person_In_Depression_Or_Will_Commit_Suicide.ipynb" target="_blank">
  <img align="center"  src="https://github.com/NavinBondade/Distinguishing-Fake-And-Real-News-With-Deep-Learning/blob/main/Graphs/button_if-github-fails-to-load-the-notebook-click-here%20(4).png?raw=true"/>
</a>
</p>
<img src="https://resize.indiatvnews.com/en/resize/newbucket/1200_-/2019/08/suicide-1565847830.jpg" width="950" height="520">
<p>Depression is one of the most widespread mental health disorders, affecting over 300 million individuals worldwide, as estimated by the World Health Organization (WHO). Its significant role as a leading factor in suicide further highlights the urgent need for effective and timely interventions. In response to this critical public health challenge, I have developed an advanced Natural Language Processing (NLP) system powered by state-of-the-art Deep Learning techniques. This innovative system is meticulously designed to detect early signs of depression and assess suicidal risk in individuals by analyzing linguistic patterns and emotional cues in their communication.

By leveraging sophisticated AI models, this tool is capable of identifying subtle indicators of mental distress that might be overlooked in traditional assessments. The system not only enhances the accuracy of depression detection but also offers crucial insights into the severity and urgency of intervention required. With the potential for wide-scale application, this AI-driven solution aims to facilitate early detection, enabling timely mental health support and ultimately reducing the risks associated with untreated depression and suicidal ideation.</p>
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
<p>To identify signs of depression and suicide risk within text, I developed a sophisticated deep learning model that integrates convolutional neural networks (CNNs) with fully connected neural network layers. The architecture is designed to effectively extract and analyze textual features that are indicative of these mental health concerns. The model employs two layers of one-dimensional CNNs, which are adept at capturing relevant patterns and features from the text data. These convolutional layers serve as the foundation for feature extraction, enabling the model to discern subtle cues that may signal depression or suicidal intent.
</p>
<p>Following the convolutional layers, the model incorporates three fully connected neural network layers that are responsible for making the final decision regarding the presence of depression or suicide risk. The ReLU activation function is utilized in all layers except the final dense layer, which employs the softmax activation function. This configuration allows the model to output probabilities that can be interpreted as the likelihood of the text belonging to a particular risk category, ensuring accurate and reliable predictions.</p>
<h2>Model Traning</h2>
<p>

The model has undergone training for a total of 150 epochs. During this process, Stochastic Gradient Descent (SGD) has been employed as the optimization algorithm. SGD is renowned for its efficiency in updating the model parameters iteratively with each training example, enhancing convergence speed and reducing computational overhead.

The categorical cross-entropy function has been utilized as the loss function, which is integral for penalizing incorrect predictions. This loss function calculates the discrepancy between the predicted probability distribution and the true class labels. By assigning a higher penalty to inaccurate predictions, categorical cross-entropy facilitates improved model performance by emphasizing the importance of accurate classification.

In summary, the combination of SGD and categorical cross-entropy ensures that the model not only converges efficiently but also achieves high accuracy by significantly penalizing false predictions and adjusting parameters accordingly throughout the training process.</p>
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
