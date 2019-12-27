# Deep-learning-pong

our main notebooks were:

reinforcement_q_learning_pole.ipynb
reinforcement_q_learning_Lander.ipynb
reinforcement_q_learning_pong.ipynb

the .loss files are simply the averaged rewards from specific runs, the .torch files are the models that resulted from those runs

the _simple notebooks are the notebooks with the same environment but not using the pixel values for learning

reinforcement_q_learning_pole_default.ipynb contains the code from https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html
which was the baseline of this this project and used to compare with our final performance of the cart pole model

fresh.ipynb was our attempt to rewrite reinforcement_q_learning_pole_default.ipynb from scratch since we thought there was a bug in it due to poor performance
however the performance was exactly the same except the computation was slower which is why we used the code from reinforcement_q_learning_pole_default.ipynb
in the rest of our project so that we could run more experiments