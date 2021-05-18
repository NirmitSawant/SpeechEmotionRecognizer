# Speech Emotion Recognizer
The way you speak, gives out how you feel. Unless you are acting xD. This model predicts your current emotional state by the way you sound.

## Algorithm
We have used MLPClassifier from sklearn. To know more about the same, click here MLPClassifier

## Database
We have used Ravdees Dataset which contains 24 actors in 8 different emotions. For sake of better accuracy, we have just considered only 4 emotions ie. Happy, Sad, Neutral, Angry!

You can download teh dataset here : [Ravdees](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/x4nth055/pythoncode-tutorials/tree/master/machine-learning/speech-emotion-recognition/data)

## How can you implement it!
-Fork the project or you can download the zip
-Delete the result folder and test.wav files
-Run the .ipynb file in order!
-You will find that result getting created if you do all the steps correctly
-Last cell of the notebook is for live testing, here we feed the live voice from your microphone of system to the model!

*Make sure that you have installed all dependencies if you are running the py file!
*If PyAudio gives out any error, excuete the code below in CMD : `apt-get install libasound-dev portaudio19-dev libportaudio2 libportaudiocpp0`
