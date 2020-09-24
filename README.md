# Recurrent Neural Network - Random name generator

Congratulations! You’re expecting a baby! Whether it’s a boy or a girl, you want your child’s name to be unique and very special. What you do is to go online and visit a whole bunch of "best baby names" list, or use random name pickers. However, these names have been used over and over by at least a few hundred others before. If this is going through your mind, then keep reading!

The solution that I am offering here is to use deep learning. First, you should collect a list of few hundred favorite names like the ones I've included here (IranianNames.txt). To generate new "cool" names, we will build a character-level recurrent neural network (RNN) and train it on the dataset. After our language model learned the patterns, we ask it to generate names you have never seen before!
