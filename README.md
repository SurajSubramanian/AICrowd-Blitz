# AICrowd
Solutions to the 5 Problems in https://www.aicrowd.com/challenges/aicrowd-blitz-may-2020/
Secured 4th place.

## FOODC
Initially the dataset was trained for certain number epochs after resizing images to size 32x32 and the weights were saved.
Then the model was trained starting from those weights, reshaping images to 64x64. Similarly, training was done by reshaping images to 128x128 and then finally for images of size 256x256.
In this way, training is done by progressively increasing image size.


## MINILEAVES
Initially, tried to train the same Resnet architecture given in the starter code for extra epochs. Then tried to use Resnet101. Finally after modifying architecture to densenet121 and trainiing for extra epochs on complete dataset after modifying valid_pct=0.00001, was able to get decent results. Maybe we can better results, if we train on other models and ensemble on them.

## DIBRD (Suraj)
Used ensemble learning with nearly 12 models to get good accuracy. Code was executed locally.
