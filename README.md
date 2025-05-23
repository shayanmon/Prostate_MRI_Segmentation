1. There are 2 folders that contain the public data with the T2-weighted MRIs and their corresponding labels. You need to download them from here: https://pi-cai.grand-challenge.org/DATA/

2. Next, run the nha_2_NIfTI.ipynb notebook to convert the public image files from nha to NIfTI files.

3. Run the 3D-Unet.ipnynb notebook to perform model training, validation, and visualize the results. The output is already saved in the current file.

4. The first run will create a checkpoints folder provides training starting points for each of the 20 epochs if you need to pause the training process. I performed the segmentation using no more than a local CPU and took about 3.5 hours to train on 240 images.
