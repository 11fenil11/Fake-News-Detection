# Fake-News-Detection
Fake News Detection using LSTM, CNN

Detect Fake News Using NLP 

Nowadays, information can easily be accessed from anywhere. It is the age of information, where an individual can access the happenings of various events around the world in the comfort of his/her own home. It has resulted in the inaccuracy and irrelevancy in updating information by people which is commonly known as fake news.

Work proposes to detect fake news using various modalities available in an efficient manner using Deep Learning algorithms such as Convolutional Neural Network and Long Short-Term Memory.


Methods: 

Fake News Classification with Deep Learning

Deep learning contains many useful and efficient algorithms when compared to other learning algorithms. In deep learning, the performance of a model is directly proportional to the amount of data that is being fed to the model. 
Fake-news detection model: -
1)Convolutional Neural Network[shift variant or space-variant artificial neural networks] :
            In CNN, there is little to no pre-processing of data required as they are more advanced.
2)Long Short-Term Memory :
            It is a type of artificial neural network architecture that is used to process multiple data points in images, speech, audio as well as text. Three gates, namely an input gate, forget gate, and output gate. LSTM has connections for feedback which are helpful in regulating the information flow through the gates.
3)Word vector :
                    Each sentence consists of words that are converted to vectors using embedding techniques. The pre word embedding models like GloVe, ELMo, fastText, BERT can be used for the purpose of obtaining a vector representation of words.


Fakeddit DataSet : 
                             The dataset is called Fakeddit as it is derived from Fake News + Reddit. Fakeddit, a novel dataset comprising of around 800,000 examples from different classifications of fake news. The dataset contains features like text, clean title, number of upvotes, comments, score, upvote ratio.
The dataset containing text is fed into the model in which the words and sentences are converted into vectors and pass through the different layers and finally get classified as real or fake in the output layer. It consists of 69954 entries of data occurrences for each column in the training dataset.
