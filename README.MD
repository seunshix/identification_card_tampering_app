<h1>Pan Card Tempering Detection</h1>
<ol>
<li>Get Images from User</li>
<li>Check for size and format of the Image</li>
<li>Change shape and size of image according to the original image</li>
<li>Convert the image to grayscale</li>
<li>Find the similarity index of the images</li>
<li>Finding the threshold of the image</li>
<li>Find contours and grab those contours using IMUTILS</li>
<li>Draw a bounding rectangle using these contours</li>
<li>Plot difference, threshold, original and tampered image</li>
<li>Compare all the images and check the similarity score to decide tampering</li>
</ol>

<h3>Step to run application:</h3>
<ol>

<li>Create a copy of the project that you want to work with.</li>
<li>Open the command prompt and navigate to the folder where you can find the 'app.py' file</li>.
<li>Create a new environment using the following command: conda create -n <environment name>
    Replace <environment name> with the name you want to give to your environment.</li>
<li>Activate the newly created environment using the following command:
        conda activate <environment name></li>
        Make sure to replace <environment name> with the name of your environment.
<li>Install the required dependencies using the following command: python -m pip install -r requirements.txt
This will install all the dependencies listed in the requirements.txt file.</li>
<li>Run the application by executing the following command: python app.py
This will start the application and you will get a URL. Copy this URL and paste it into your web browser to access the application.</li>

<li>Finally, to test the application, you can use the images provided in the sample_data folder.
</ol>
That's it! These steps should help you get started with running the application.
