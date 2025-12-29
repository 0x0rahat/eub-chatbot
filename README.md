# eub-chatbot

Installation and Setup
--------------------------------
This project requires the following packages and dependencies:

*Python 3.6 or higher
*TensorFlow 2.x or higher
*NumPy
*NLTK
*Flask
*Flask-SocketIO
*JSON
To install these packages, you can use pip:

```pip install tensorflow numpy nltk flask flask-socketio json```

Training the Model
-------------------------------
To train the model, run the train.py script:

```python train.py```
This will train the model on the intents defined in the intents.json file.

If you want to modify the intents, you can edit the intents.json file and then retrain the model.

Running the CLI Interface
-----------------------------------
To run the chatbot on the CLI interface, run the chat.py script:

```python chat.py```
This will start the chatbot on the command line.

Running the GUI Interface
-----------------------------------------
To run the chatbot on the GUI interface, run the app.py script:

```python app.py```
This will start the chatbot on the GUI interface and generate a link. Open the link in your browser to interact with the chatbot.
