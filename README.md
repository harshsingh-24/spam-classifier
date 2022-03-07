<h1 align = "center"> Spam Classifier </h1>
<p align="center"> 
<img src="gifs/spam-classifier.gif" alt="Animated gif of spam clasffication" height="382px">
</p>
I have developed a spam classifier program in Python which classifies given emails as spam or ham using Multilayer Perceptron (MLP).

<h2> 🌟 Overview</h2>
I used the [Apache SpamAssassin public data](https://www.google.com) to train and test a ML-based classification model based on Multilevel Perceptron because of their high efficacy in terms of precision and recall. If you want to run this project, you only need the dependencies (see below). No extra files are needed as the Jupyter notebook will download all the required files.

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 1 executable file, 3 text files as well as 2 directories for training and testing purposes. The description is as follows: </p>
<h4>Executable Files:</h4>
<ul>
  <li><b>spam-classifier-optimized.ipynb</b> - A  Jupyter Notebook consisiting of all the functions required for training, testing and classification of the emails. Includes all functions required for classification operations.</li>
</ul>

<h4>Output Files:</h4>
<ul>
  <li><b>model.txt</b> - Contains information about the vocabularies of the train set, such as the frequency and conditional probability of each word in Spam and Ham classes.</li>
  <li><b>result.txt</b> - Contains information about the classified emails of the test set.</li>
  <li><b>evaluation.txt</b> - Contains evaluation results table as well as Confusion Matrix of Spam and Ham classes.</li>
</ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>train directory</b> - Includes all emails for the training phase of the program.</li>
  <li><b>test directory</b> - Includes all emails for the testing phase of the program.</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

