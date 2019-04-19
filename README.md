# IMDB-Sentiment-Analysis
Sentiment analysis of IMDB Dataset using RNN and LSTM

A callback is a set of functions to be applied at given stages of the training procedure. You can use callbacks to get a view on internal states and statistics of the model during training. You can pass a list of callbacks (as the keyword argument callbacks) to the .fit() method of the Sequential or  Model classes. The relevant methods of the callbacks will then be called at each stage of the training.


#  I have used model checkpoint to reduce overfitting and it aslo helps us save the best model and its weights.
keras.callbacks.ModelCheckpoint(filepath, monitor='val_loss', verbose=0, save_best_only=False, save_weights_only=False, mode='auto', period=1)

# I aslo used Early stopping callback so that the model stops training or early stops as soon as the validation accuracy does not improve or the loss does not decrease.
## Here is the Syntax

keras.callbacks.EarlyStopping(monitor='val_loss', min_delta=0, patience=0, verbose=0, mode='auto', baseline=None, restore_best_weights=False)

# You can run this code on google colab to save time and also download the IMDB Dataset there.
