# Deep-learning-chatbot
In this Python project with source code, we are going to build a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.

- Intents.json – The data file which has predefined patterns and responses
- train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot
- Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary
- Classes.pkl – The classes pickle file contains the list of categories
- Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons
- Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot

# Here are the 5 steps to create a chatbot in Python from scratch:

1. Import and load the data file
2. Preprocess data
3. Create training and testing data
4. Build the model
5. Predict the response
