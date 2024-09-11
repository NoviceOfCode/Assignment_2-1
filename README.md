# Assignment_2-1
I'm re-submitting code from the Hands-On 9/10 project because it seems to fulfill conditions as our team is considering using separate models for separate exercises, and I chose this because I'm confused as to my team's current submission for the HW for 9/11.

# Model
The model is a simple 7-layer keras model with dropout. Input layer is ReLU and has input dimensions of 68. hidden layers are allowed to switch between relu and tanh to test for better results.

# Dataset
The dataset is plank exercises done for a thesis project from the https://github.com/NgoQuocBao1010. The data captured is only of himself and his family/friends. It is not clear the composition of the data between himself and his family. Examples he provides of the original video footage suggest that he recorded most exercises from the same angle as well. We hope to later-on combine this planking dataset with other planking exercises recorded for our model.

# Results
The model created is a model that has 0.9912342429161072 accuracy for detecting correct plank vs improper back placement plank. 

# Instructions
**Training Model** - As long as you have all the libraries needed, you should only need to run "Model Training.ipynb" in the src folder.That should automatically produce the necessary model

**Use Model** - For this, imports can be trickier. We have the model able to be deployed through Streamlit. Your tensorflow library and potsobuff library on python will may need to have their versions adjusted. In a terminal, in the src directory, type _streamlit run app.py_. This command should give you a link to local host to show you a model that allows you to input values that correspond with the position of body parts. Once you place all wanted values, the model will give you a prediction.
