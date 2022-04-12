This is a Natural Language Processing (NLP) model that divides the input transcription into three categories: action, object, and location.

According to the data, there were 6 action labels, 14 object labels, and 4 location labels. We might have utilised pre-trained models because the text in the given dataset corresponds to a very gaint data space (transfer learning). However, in this project, word2vec, LSTM, and other techniques are employed to create a custom model.
These are the steps taken to save the desired outcome.
1. Organize the information in the following manner: We can't feed text to the model because it's in text format, therefore we'll have to convert it to a numerical value first. Using One-Hot encoding, the [activity, object, and location] are converted to numerical foamt. Transcrypt is cleaned of any stopwords, punctuation, and other grammatical errors, and it is converted to lowercase.
2. Training the model: [action, object, and location] are the target classes that must be predicted, with "Transcript" as the X value. The model is made up of three layers: embedding layer, lstm layer, and dense layer.
