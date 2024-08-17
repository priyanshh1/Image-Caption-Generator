Image captioning is a task that involves generating textual descriptions for images. This project combines computer vision (CNNs) and natural language processing (RNNs) to achieve this.

**Key steps:**

Feature extraction: Uses a pre-trained CNN (DenseNet201) to extract features from images.

Text preprocessing: Cleans and prepares caption text for training.

Model architecture: Employs an encoder-decoder framework with CNN and LSTM.

Training: Trains the model on image-caption pairs.

Inference: Generates captions for new images.

**Challenges and future work:**

Overfitting: The model currently overfits due to limited data.

Caption quality: Generated captions can be redundant or inaccurate.


