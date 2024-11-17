The brilliance of the human brain sees and comprehends every thing around. The very need of a human mind to quanitify and classify every object in sight is why we have a name or a caption of sorts for every visual feed and identity, a quality researchers have been dying to implement onto a live computer. Hence, today we have the Computer Vision. with the advancements in Deep learning techniques, availability of huge datasets and computer power, we can build models that can generate captions for any image.

In this Python based project my team has implemented image caption generation using deep learning techniques of Convolutional Neural Networks(CNN) and LSTM(Long Short Term Memory), a type of Recurrent Neural Network(RNN).


Image Caption Generation utilises computer vision and natural language processing concepts to identify any image and provide a crisp and direct description of it in a natural language like English.

In this Python project, we have implemented the caption generator using concepts of CNN and LSTM. Initially, the features of the image are extracted via Xception which is a CNN model trained on imagenet dataset. Later, the features are fed into the LSTM model which is responsible for generating the image caption

We have used the following dataset to construct our ML model:
 .Flicker8k_Dataset 
 .Flickr_8k_text
The Flickr_8k_text folder contains file Flickr8k.token which is the main file of our dataset that contains image name and their respective captions separated by newline(“\n”). 


The following are the necessary libraries we used to preprocess the data, extract the features, train the model and produce a caption:
 .tensorflow
 .keras
 .pillow
 .numpy
 .tqdm
