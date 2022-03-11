# Chess Piece Detector 

This is an end to end Chess Pieces Object detection Project where the pieces in the chess are identified as pawn, king, knight etc.

#### About the Datatset

    I have collected this dataset from Roboflow. The dataset is of Chess board photos and various pieces. 
    All photos were captured from a constant angle, a tripod to the left of the board. The bounding boxes of 
    all pieces are annotated as follows: white-king, white-queen, white-bishop, white-knight, white-rook, 
    white-pawn, black-king, black-queen, black-bishop, black-knight, black-rook, black-pawn. 
    There are 2894 labels across 292 images. 
    
[Link to dataset - Click Here](https://public.roboflow.com/object-detection/chess-full)

#### For Running the Project:

    I have used Tensorflow 2.x for object detection. 
    Kindly visit the official reporsitory for tensorflow and download the models folder for running the project 
    you just need few folders from the reserch folders copy those and keep them in the extracted folder for this
    repository. Your directory should be loooking like below image.
    
 ![Capture](https://user-images.githubusercontent.com/55132850/155108555-133f5263-e013-45c0-8731-2548489e0101.PNG)
   
 <!-- > Open the project in Pychram or VS code 

    > Create a new Conda environemnt 
    - File > Settings > Python Interpretor > Add > #### Results:Create new conda environment
    
    > Activate the enviironment in terminal conda activate "ENV_NAME" 

    > Run : pip install - requirements.txt

    > Run the project find it on http://127.0.0.1:8000/

    > Kindly use some of the images in sample images folder for testing it or you can see the SS below. -->

#### Results:

    This is how your web application will look. Just cick on upload and upload the image from sample images folder 
    and click on predict to see the results. 

Step 1 : Click on Upload and choose the image.

![home1(1)](https://user-images.githubusercontent.com/90520726/157794159-04228e87-1f35-4225-b0a9-340110545cc6.png)

Step 2 : Now Click on Predict to perform the object detection using the custom model created. 

![home0](https://user-images.githubusercontent.com/90520726/157793992-b1c96018-3a6e-4f1b-8028-19124b4e674b.png)

Step :3 Your Results will be shown lik ebelow. It will also be saved in the saem older in your directory.

![home 2(2)](https://user-images.githubusercontent.com/90520726/157794038-75fa5ce7-17ce-42de-8f7d-50e1878e25e8.png)

      
   
