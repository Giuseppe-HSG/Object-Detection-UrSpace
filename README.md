# Object-Detection-UrSpace

We trained our custom detection model which is able to identify the various classes of objects within images from the Homestyler website. Theoretically, the pre-built configurations from UrSpace or the ones pesonalised on the website would be sent to the object- detection model which is able to identify the type of furniture that the AMR should move. In addition, the bounding boxes could be scaled to represent the true dimensions of the room in order for the robot to know where the identified furniture should be moved within the room.

## Try it Yourself!

The **Final Object Detection Model** Notebook allows you to run the model yourself. The **Room Configurations to test** folder has a number of configurations to try the model with. In addition, you can create your own configuration on Homestyler and run it in the detection model.

## Full Trained Model

We used the AI guy's Notebook and configured it for our own model. Our full training Model can be found under the **Full Yolov4 Training Model** Notebook above.

### Training and Testing 

The **Training and Testing File** file above shows the images we used to train and validate the dataset as well as their coordinates using the LabelImg program.

### Configuration Files

The **Yolov4 - configuration files** has all the documents used to configure our neural network. It includes the **yolov4-obj.cfg** file which has been configured to our model.

### Backup Folder

The folder with the backup of the weights we used to train the neural network was too large to be uploaded on Github. Therefore, the link is:(https://drive.google.com/drive/u/0/folders/1d1O_AeN0GWnEwBUJfPo9i3BCQ1bHkc8m)

The link to all the documents on Google Drive is: https://drive.google.com/drive/folders/1_mqlNtqyU-URfvZBQiDwX6uKofE734rF?usp=sharing
