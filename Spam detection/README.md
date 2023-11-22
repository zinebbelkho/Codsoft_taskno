
<h1 style="color:red;text-align:center">SPAM SMS DETECTION</h1>
<h2>Description</h2>
Spam sms detection consists of building a model that can classify SMS messages as spam or legitimate.
The proposed approach for detecting and classifying messages consists of three modules.<br>
<ul><li>
Pre_processing: is accomplished to remove irrelivant parts of data before extracting any feature.The preprocessing is based on two steps tokenization and stop words removal
tokenization: splits text into a sequence of tokens where each token representes a single word based on whitespace character
Stop words removal: removes meaningless words that occur frequently in the review's text which can result in improving the response and reducing the index's space</li><br>
<li>
Extraction module: is an important module because the selection of the appropriate set plays a key role in classification. N-gram is one of the most commonly used feature extraction method in classification. It's a sequence of n contiguous words in a text.The most frequently used N-gram is Uni-gram (one word), Bi-gram (two contiguous words), and Tri-gram (three contiguous words).</li><br>
<li>
Spam detection: the classification of messages can be performed using several machine learning classifiers such as k-nearest neighbors,neural network,logistic regression and more. By the end we can use a technique called Majority voting ensemble classifier to decide the prediction that take a highest votes from the multible predecting models.
</li></ul>
