# CodeML Hackathon

## Information
 
CodeML was an hackathon organised by PolyAI on Nob 21, 22. Spread over 48 hours, it consisted of a series of challenges on machine learning of increasing difficulty. 

We participated in teams of 4 in different challenges and we posted here our code for challenge 4 and challenge 5.

## Challenge 4

Consumers have left comments (texts) of the last product they just used. We would like to know if it is possible to determine if the comments are positive or negative in the future for other products.

This challenge is simple: use machine learning techniques to create a model that predicts what the positive or negative feedback is on using old feedback collected

### What we did
#### First version

- Load the dataset
- NLP Processing: Tokenizing, Cleaning, Normalization
- Transform the text to tf-idf features
- Train a baseline model (Logistic Regression)

#### Second version using Google Electra
- Write the code for Google Electra model using simpletransformers lib
- Tune it

#### Results 
We are pleased to have been able to test pre-trained models that represent the state of the art in machine learning. We could directly experience the effectiveness of such models because by using Electra we scored at the top of the Kaggle leaderboard.
<p><img src="https://github.com/kumarmanishjha/CodeML-Hackathon/blob/main/challenge4/submissions/pic.png" width=35% height=35%></p>
We are looking forward to see the solutions of the others participants.

## Challenge 5

You have a zip file of images of 10 differents objects: **'airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck' **

This challenge is simple: use machine learning techniques to recognize these 10 different classes

So the data here is a zip file containing multiple images in PNG format and labels for training in text file format.
