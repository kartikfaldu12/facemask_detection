Realtime facemask detection

In the above project I used webscrapped data with classes people wearing mask and no mask and trained a model named train_model. Also plotted the graph between epoch(number of passes of the entire training dataset) and loss/accuracy. The trained model is then used to check realtime detection through the webcam feed. 

Usage:

Step 1:Exceute train.py (Training the model with the appropriate dataset and weights)

Step 2:add the model weight in test.py program and execute it.

Prerequisites:

1) Make sure that all the required libraries are installed. (For reference : libraries mentioned in requirements.txt, install in command prompt using pip)
2) Checkup whether the mentioned filepath of the dataset and face_detector are correct, as it may end up with an error if that is not correct.
