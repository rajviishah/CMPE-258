Write a deep recommender system system/colab which does both item to item, and user to item recommendation  models
which utilizes all the state of art techniques in one system
a) cnn, gru and bag of words models jointly for forming embeddings
b) dcn layer for  feature crossing
c) sequential model 
d) Deep recurrent networks for embeddings generation (uses multiple dens layers / non linearities before embedding)
e) deep ranking using list wise ranking 
f) scalable deep retrieval using scann
g) Multi task losses for multi objective loss (for both ranking and retrieval)
h) SNGP for out of box distribution of input example detection
i) Bandit algorithm for sampling multiple recommenders
j) tf-serving for serving and tfx for training 
All these are provided in colabs/setup in https://docs.google.com/presentation/d/1E4EqGILyfiRiWdtU1Enp0jhPPAJqnlrAYiiDyuaTqgQ/edit#slide=id.g122817339fb_0_598 (Links to an external site.)

Write a detailed read.me with all details and screenshots of running system

Note that this is an important assignment which utilizes all the skills you learnt (cnn, gru, embeddings etc.,.) in holistic single end2end application. i recommend folks who are not interested in marks also attempt this.
