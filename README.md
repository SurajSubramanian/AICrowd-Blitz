# AICrowd
Solutions to the 5 Problems in https://www.aicrowd.com/challenges/aicrowd-blitz-may-2020/

## FOODC
Initially the dataset was trained for certain number epochs after resizing images to size 32*32 and the weights were saved.
Then the model was trained starting from those weights, reshaping images to 64*64. Similarly, training was done by reshaping images to 128*128 and then finally for images of size 256*256.
In this way, training is done by progressively increasing image size.
