# ChatBot-NMT
Chatbot using advanced NMT (Seq2Seq) RNN to chat !
# Collecting Data
There is already training a sample data in "data" folder. Sample data is produced using Reddit 2015 January monthly entrys,comments whatever you call it.
But if you want to use your own data you can go to https://pythonprogramming.net/data-structure-chatbot-deep-learning-python-tensorflow/
# Training Data
When your data is ready, train it train.py.
After training completed your model will be in "model" directory. You can use your model using inference.py
You can change you epoch number in setup/settings.py hparams{epoch:}. The default is 3 epoch and you have to et learning rate. I mean if you want to train your data for 5 epochs, you need to set (eg:) [0.01,0.01,0.01,0.01,0.01]. But i recommend you to use different learning rates.
# Testing Data
You can interact wtih your chatbot using inference.py in root directory.

# References:
This project is based on tutorial series. See: https://pythonprogramming.net/chatbot-deep-learning-python-tensorflow/

# You reached to the "END" :)







