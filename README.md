TEXT ANALYSIS
This is an ai model that takes in text and returns the nature of the text, i.e. good, bad or neutral.
It can prove especially useful in comprehending student or cuustomer reviews about lecturers, topics or even work environments.

The training dataset was preprocessed using tokenization, stemming, and lemminization.
It was then used to train an LSTM (long short term memory) ai model.
Unfortunately, the model performed poorly in accuracy testing.
Consequently, we employed a pre-defined Bert (Bidirectional Encoder Representation from Transformers) ai model.

Using the Nemo library to help ease model-comprehension, we trained the Bert model.
The new model yielded better scores during accuracy testing.

Unfortunately, this also meant the model was too large to be deployed with Visual Studio Code which is why the deployement file is a Google Colab file.
Hence, our deploying it in the file "student_feedback_analysis_deployement" in this same repository.
