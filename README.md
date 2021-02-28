<h1>SUBMISSION OF EVERGREEN CLASSIFICATION CHALLENGE</h1>
<p1>The goal of our project was to study a
specific instance of this broad and vital web
classification problem and developing a
successful prediction system. We selected
the StumbleUpon Evergreen Classification
Challenge, that requires building a classifier
to categorize webpages as evergreen or
ephemeral. Most news articles or seasonal
recipes are relevant for only a short period of
time while others are relevant forever and
can be recommended to users anytime.
Therefore, based on the relevancy of a
webpage, it can be classified as “evergreen”
or “non-evergreen”.</p>
<h2>APPROACH</h2>
<p2>
  <ol>
  <li> Firstly, I have imported all the necessary libraries, packages and frameworks like Numpy,Pandas, Sklearn, Seaborn, Matplotlib, NLTK, Tensorflow, Keras and Transformers</li>
    <li> Read the given datasets train.tsv and test.tsv </li>
    <li>Then used various visualisation to find the correlation between the data</li>
    <li>Now that all the necessary steps are done, I have chosen A Transformer based Machine Learning Technique, DistilBERT.</li>
    <li>The data was preprocessed then. The data was shuffled later for better model quality.</li>
    <li>DistilBERT Tokenizer and Model is imported and initialized.</li>
    <li>The text data is transformed into tokenised ids and attention masks after padding.</li>
    <li>A neural network using DistilBERT embedding is defined. Here, the structure is being inspired by the <a href="https://github.com/TinySuitStarfishAbhi/StumbleUponClassifier/blob/master/Approach.pdf">article</a>. I have also taken help from this <a href="https://github.com/aishikasaha/evergreen_classification/blob/main/RoySaraiya_StumbleUponClassification.pdf">article</a> too.
     <li> The parameter loss, metric and optimiser, the model was fit and trained using training data.</li>
    <li>The predictions were made and the data was analysed, thereby generating the F1 score. The precision and recall value of each class is:
    <img src="https://github.com/aishikasaha/evergreen_classification/blob/main/Capture.JPG"></li>
    <li>The submission csv was created.</li>
    
  </ol>
