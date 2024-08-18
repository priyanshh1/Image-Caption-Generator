This project deals with Image captioning which is a task that involves generating textual descriptions for images and we do this by combining computer vision (CNNs) and natural language processing (RNNs) .

**Key steps:**

_Feature extraction_: Uses a pre-trained CNN (DenseNet201) to extract features from images.

_Text preprocessing_: Cleaned and prepared caption text for training.

_Model architecture_: Employed an encoder-decoder framework with CNN and LSTM.

_Training_: Trained the model on image-caption pairs.

_Inference_: Generated captions for new images.

**Challenges and Future work**

_Overfitting_: The model currently overfits due to limited data.

_Caption quality_: Generated captions can be redundant or inaccurate.


