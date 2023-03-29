# Pan Card Tempering Detection

### Steps to complete project
1. Get Images from User
2. Check for size and format of the Image
3. Change shape and size of image according to the original image
4. Convert the image to grayscale
5. Find the similarity index of the images
6. Finding the threshold of the image
7. Find contours and grab those contours using IMUTILS
8. Draw a bounding rectangle using these contours
9. Plot difference, threshold, original and tampered image
10. Compare all the images and check the similarity score to decide tampering


### Step to run application


1. Create a copy of the project that you want to work with.
2. Open the command prompt and navigate to the folder where you can find the 'app.py' file.
    - Create a new environment using the following command: conda create -n <environment name>
    - Replace <environment name> with the name you want to give to your environment.
3. Activate the newly created environment using the following command:
        conda activate <environment name>
    - Make sure to replace <environment name> with the name of your environment.
4. Install the required dependencies using the following command: 
        python -m pip install -r requirements.txt
    - This will install all the dependencies listed in the requirements.txt file.
5. Run the application by executing the following command: python app.py
    - This will start the application and you will get a URL. Copy this URL and paste it into your web browser to access the application.

6. Finally, to test the application, you can use the images provided in the sample_data folder.

That's it! These steps should help you get started with running the application.
