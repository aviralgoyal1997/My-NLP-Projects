# My-NLP-Projects


<h3>1.Text Cleaning </h3>
In text_cleaning.ipynb we will be learning how to prepare document before applying model or how to clean document and in last we will have document converted into tokenized words with their frequency  which we will be using in word2vec embedding(representation of words) for our models.
For more information just have a look at my sentiment_prediction_model_trained_on_imdb_reviews,in that in starting representation of sentence is basically frequency of those words in that data.

<h3>Similarity between words</h3>
First install spacy package and trained model then run this code.
$ sudo python2 install spacy 
$ sudo python2 -m spacy download en_core_web_md


<h3>2.Similaritybetween sentences </h3>

In similarity_sentence_document.ipynb we first gonna split document into sentences and then we gonna convert document into matrix of count of tokens means each row represents sentence and each column represent word and value will be count of that word in that sentence,here total no of columns will be totall no of words in document after cleaning.Then we gonna use cosine similarity to find similarity matrix between sentences by dotproduct between their rows in count matrix.
<h3>Difference betwwen matrix we used here and in imdb sentiment project</h3>
In imdb model we first found out words and their frequency and alloted them no as how frequent they are like no 1 is most frquent word.Then we convert each sentence into matrix of shape 1Xn where n is no of words in sentence and value is how frequent that word is in the document and then later in embedding we made matrix with one hot encoding means total no of columns =total no of words all over and value =1 at positions where columns = values of how frequent those words(present in document) are. 

<h3>3.TextRank approach for text summarization (Graph base approach)</h3>
<href>https://wordpress.com/post/datasciencebasicsblog.wordpress.com/1034 </href>

<h3>4.Feature Base approach for text summarization </h3>
Give this approach a look at <href>https://datasciencebasicsblog.wordpress.com/2018/06/02/text-summarization-approaches/ </href>
Reference for implementation : <href> https://github.com/xiaoxu193/PyTeaser </href>

<h3>5.Topic Modeling by LDA approach</h3>
Code implementation : LDA_Topic_Modeling.ipynb

See here <href>https://datasciencebasicsblog.wordpress.com/topic-modeling-with-python/  </href>
<h3>6.Language Model using RNN </h3>
To know about language model and RNN and its implementation steps go to :<br>
<href>https://datasciencebasicsblog.wordpress.com/2018/03/03/nlp-recurrent-neural-networks-and-language-models/<href>
<href>https://datasciencebasicsblog.wordpress.com/2018/08/20/making-a-language-model-using-python/</href>

