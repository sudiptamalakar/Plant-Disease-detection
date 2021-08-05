# Plant-Disease-detection
Images of the apple leaf is used for determining the disease of the Apple tree using CNN.

#plant_image_crop_and_resize.ipynb have the function for cropping,resizing the image.
It also has the method store an image array into a .csv file

#Plant_Patho_2021_CNN.ipynb the csv file is loaded and converted again into image array.
After that the labels are split and using a function we create new columns for labels.
Then the CNN model is built and trained the model with the images of apple leafs.

First run the plant_image_crop_and_resize.ipynb for cropping and resizing the image then run Plant_Patho_2021_CNN.ipynb for the training the model
