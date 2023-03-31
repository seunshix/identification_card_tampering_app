# Identification Card Tampering Detection 

This project aims to detect tampering or falsification identification cards using computer vision techniques. By analyzing the image's structural content, it can identify tampering through the addition or removal of information or alterations to the image. The project has practical applications for government agencies, financial institutions, and employers who require identity verification. It can be used to verify PAN cards during account opening or loan application processes, and detect tampering or falsification of other identification documents such as voter IDs, passports, and driver's licenses. The project enhances identity verification processes, improves security, and prevents fraud.

### For a step-by-step walkthrough of the project, please check out the [Colab notebook](./pan_card_tampering.ipynb)


### Step to run application


1. Create a copy of the project that you want to work with.
2. Open the command prompt and navigate to the folder where you can find the ```'app.py'``` file.
    - Create a new environment using the following command: ```conda create -n <environment name>```
    - Replace ```<environment name>``` with the name you want to give to your environment.
3. Activate the newly created environment using the following command:
        ```conda activate <environment name>```
    - Make sure to replace ```<environment name>``` with the name of your environment.
4. Install the required dependencies using the following command: 
        ```python -m pip install -r requirements.txt```
    - This will install all the dependencies listed in the requirements.txt file.
5. Run the application by executing the following command: ```python app.py```
    - This will start the application and you will get a URL. Copy this URL and paste it into your web browser to access the application.

That's it! These steps should help you get started with running the application.

### Screenshots of the running app
![Prediction with original card](./images/with_original.PNG 'Prediction with original card')
![Prediction with tampered card](./images/with_tampered.PNG 'Prediction with tampered card')
