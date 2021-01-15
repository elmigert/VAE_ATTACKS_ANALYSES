# VAE_ATTACKS_ANALYSES
Different VAE networks are tested on attacks. 


This code is design to run on google colab, however one can also easily modify it to run locally. To use our model, 
create a google account and mirror this folder directory in the root directory of your google drive. if you do not 
wish to see the model paramters or reconstructed images, simply copy all the file in the colab notebook folder to 
your own colab notebook folder. Create a new jupyter notebook in google colab and run the following lines:

from google.colab import drive
drive.mount('/content/drive')
import os
!cp drive/MyDrive/"Colab Notebooks"/replay_buffer_v2.py .
!cp drive/MyDrive/"Colab Notebooks"/segment_tree.py .
!cp drive/MyDrive/"Colab Notebooks"/datasampler.py .
!cp drive/MyDrive/"Colab Notebooks"/critic.py .
!cp drive/MyDrive/"Colab Notebooks"/model_fc.py .
!cp drive/MyDrive/"Colab Notebooks"/model_cnn.py .
!cp drive/MyDrive/"Colab Notebooks"/attacks.py .
!cp drive/MyDrive/"Colab Notebooks"/linearschedule.py .
!cp drive/MyDrive/"Colab Notebooks"/datasampler.py .
!cp drive/MyDrive/"Colab Notebooks"/test.py .
!cp drive/MyDrive/"Colab Notebooks"/train.py .

then u will be ready to run train.py or test.py on your google colab notebook.

for examples of training code, check out Colab Notebooks/train_vae.ipynb

Unfortunately, model weights are too large to be uploaded. if u are interested in seeing the model weight, send me a email xurali@student.ethz.ch and I will share a link to the google drive to u.
