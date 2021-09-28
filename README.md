# WordsAndColours

Using a combination of CNNs and Word2Vec embeddings (downloaded from https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing) to generate colours from a group of words. 

The model is trained using the word vectors found in the Word2Vec embeddings, and an Adobe photoshop colour pallette file, which contains names and RGB representations of 1500 colours. 
Additionally, I have artifically added repeated samples of basic colours to the training data. The number of repetitions of the basic colours is considered a hyperparameter, which can be adjusted to increase the importance of learning the representation of the basic colours: Red, Blue, Green, Cyan, Magenta, Yellow and White.

The model produces some very interesting results. For example, it is able to learn the chromatic meaning of words such as deep, light, stormy, calm, etc.
