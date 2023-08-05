In the src folder, you will find a Jupyter Notebook file (Final Project SRCNN.ipynb) which loads data, trains the data, and validates it.

The input data consists of the General100 and T91 dataset which is divided into patches. The patches serve as the training data for the Convoluted Neural Network (CNN).

In this model, I have used Mean Square Loss (MSE) and Peak-Signal to Noise Ratio (PSNR) to keep track of the progress during epochs. 

The validation data consists of Set5 and Set14 (in all 19 images).

Check the last few code cells to see image patches, loss plots, PSNR plots of validation and training data, patches, comparison of Ground Truth (original) image, Bicubic 2x scaled image and the Super Resolved Image generated after passing it through the SRCNN.

Patches and Original Images can be found in the '/inputs' directory under appropriate sub-folders.
Similarly, in the directory '/outputs' you will find loss plots and resolved images under appropriate sub-folders. 

Note: The results may not be visually evident due to limited computing power and epochs (sadly, I don't have a GPU). However, the mathematical results are quite satisfactory as the PSNR reaches a value of ~32.
