Project Name: Next Word Predictor Using LSTM
Overview:
This project builds a next word prediction model using Long Short-Term Memory (LSTM) networks. The model is trained on a dataset of frequently asked questions (FAQs) to predict the next word in a sequence based on prior words. The objective is to develop an intelligent text completion system.

Key Features:
Text Tokenization: Converts the input text into sequences of numerical tokens.
LSTM-based Sequential Model: Utilizes two LSTM layers for efficient text prediction, handling context across word sequences.
Next Word Prediction: Generates the next word based on the input sequence by using a pre-trained tokenizer and padding sequences for consistent input length.


Dataset
Source: A list of FAQs related to a Data Science Mentorship Program.
Text Preprocessing: Tokenized the FAQ text to generate sequences of input-output pairs for LSTM training.
Model Architecture
Embedding Layer: Embeds the input tokens into dense vectors of a fixed size.
LSTM Layers: Two LSTM layers, one with return_sequences=True and the other as the final LSTM layer, to capture long-range dependencies in the text.
Dense Layer: Output layer with a softmax activation function to predict the next word.
How to Use
Input a sequence of words.
The model will predict the next word in the sequence.
The output sequence will display the predicted next word after every iteration.
Evaluation
Accuracy: The model achieved a training accuracy of 96.02% after 100 epochs.
Conclusion
This LSTM-based next word predictor is capable of generating contextually relevant next words based on input sequences. It can be used in text completion applications or integrated into chatbot systems.
