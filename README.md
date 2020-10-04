# Face-Mask-Detection-for-COVID19

# Please click on the link given below to access the trained face mask detection model

https://drive.google.com/file/d/1qUf6FlW7MfMOyQY9lrfPLLfp43qaApKJ/view?usp=sharing

# Please click on the link given to access the accompanying presentation

https://docs.google.com/presentation/d/1EANFCyFkPBmxxZ1tcLx0snnGBwvZHd_X8Ot6U_Ut2l0/edit?usp=sharing

# Please click on the link given to access the dataset that the model has been trained on

https://drive.google.com/drive/folders/1OfuBi6uDRBO8kvwuyZd_pS2P8lT0lO_H?usp=sharing

The dataset is an amalgamation of two datasets:
1. Collected from Prajna Bhandary https://github.com/prajnasb/observations/tree/master/experiements/data
2. Collected from Chandrika Deb https://github.com/chandrikadeb7/Face-Mask-Detection/tree/master/dataset

# How to run the program

1. Download Face_Mask_Detection_Training_on_Google_COLAB_part.ipynb file to Google Drive account, and open it in a Google Colaboratory notebook. Change the Runtime to GPU. To mount the Google Drive, run first two cells one by one. Give authority permissions wherever asked.
2. Save the dataset to Google Drive and add its directory path to the next cell. If properly done, the dataset with two separate folders of with_mask and without_mask will be printed.
3. Run the next cell to process the images and split the dataset intro training and testing.
4. Run the next three cells to create and visualize the CNN model.
5. Run the next cell to train the model.
6. Run the next cell to plot two graphs, one for loss and one for accuracy, to see the progress of each with the increase in number of epochs.
7. The best_model.h5 file will be saved to the same Google Drive directory where the Training file has been saved. Download it to a local folder.
7. Download Webcam Check if Mask On or Off.ipynb file to the same local folder where the best_model.h5 is saved, and open it with Jupyter Lab.
8. Run the cell. To check if the warning email has been received, use the dummy authority email address lizzy.darcy.harry.potter@gmail.com and the password prideandprejudice
      *The Tensorflow version used in Google Colaboratory and that in Jupyter Lab must remain the same.
      *The webcam is available and given permission to be accessed.

*** For any queries, please email me at tahseena.mahmud@gmail.com
