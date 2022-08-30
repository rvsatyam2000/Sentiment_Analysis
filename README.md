# Sentiment Analysis
<ol>
<li> Downloaded twitter dataset from kaggle </li>
<li> Used pandas library to read dataset </li>
<li> Checked null values </li>
<li> Removed rows containing null values </li>
<li> Removed Irrelevant data </li>
<li> Dropped columns which are of no use </li>
<li> Imported <b> nltk</b> library </li>
<li> In sentiment analysis, words like [not, no, aren't, ...] are important. So, from stopwords, these words are removed  </li>
<li> Imported <b> wordnetlemmatizer</b> for lemmatizing </li>
<li> <b> Stopwords </b>  and wordnetlemmatizer applied simultaneously on sentences</li>
<li> <b> One hot encoding </b> is used for sentiments [negative, positive, neutral]. </li>
<li> <b> Tokenizer </b> is used for converting each word of sentence into an integer </li>
<li> <b> Padding </b>  is used for creating dataset of same size </li>
<li> Data is split into train and test data </li>
<li> Data is trained using <b> LSTM </b> deep learning neural network</li>
<li> <b> Dropout </b> is used to avoid overfitting </li>
<li> <b> Early stopping </b> is used </li>
<li> Finally, model is created, which gives <b> 89% accuracy</b> </li>
<ol>
