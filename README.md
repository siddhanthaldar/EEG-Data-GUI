# EEG-Data-GUI

This repo contains a GUI for displaying EEG signal Data obtained from the Emotic Epoc+ containing 14 Channels.

The code **gui.py** uses randomized data in the range of 4100-4300 (range of signal data obtained from the headset while testing). The images **b-.png** are the actions classified by the CNN-based classifier taking EEG data as input. The  images **t-.png** are the actions performed by the user wearing the headset in order to make the classifier classify the desired action. This was a part of a project named *"Armoid"* where we made a brain controlled robotic arm.

**INSTRUCTIONS :**

Anyone planning to use this must alter the class *Data* to take as input the data from the headset set. Here, we have set the window length(number of time steps over which the data is accumulated before passing it through the classifier) to be 150 in order to build the input matrix for the CNN-based classifier.

