# Emotion Detector Project

This project utilizes a Vision Transformer (ViT) model for facial expression recognition using the FER-2013 dataset.

## 1. Setup Virtual Environment (venv)

To set up the project environment, you need to create a virtual environment and install the required packages.

### Steps:

1. Open a terminal (cmd, bash, etc.)
2. Navigate to your project directory:

   ```bash
   cd /path/to/your/project
3. Create a virtual environment using venv:

    ```bash
    python -m venv tfod
4. Activate the virtual environment:

    On Windows:

        tfod\Scripts\activate

    On MacOS/Linux:

        source tfod/bin/activate

5. Once activated, you will see (tfod) before your terminal prompt, indicating the virtual environment is active.

## 2. Install Required Packages

The project requirements are listed in the requirements.txt file. Install them using the following command:

    pip install -r requirements.txt

## 3. Download the FER-2013 Dataset from Kaggle

To download datasets from Kaggle, you need to set up your Kaggle API credentials. Follow these steps:

1. Step 1: Install the Kaggle CLI
    ```bash
    pip install kaggle
2. Step 2: Setup Kaggle API Credentials

Go to Kaggle and log in.

Navigate to "My Account" and scroll down to the "API" section.

Click on "Create New API Token". This will download a file named kaggle.json.
Place the kaggle.json file in the following directory:

On Windows: C:\Users\<Your-Username>\.kaggle\
On MacOS/Linux: /home/<Your-Username>/.kaggle/
Alternatively, you can set the environment variable to point to your kaggle.json location.

3. Step 3: Download the FER-2013 Dataset
Once the API key is set up, use the following command to download the dataset:
    ```bash
    kaggle datasets download -d msambare/fer2013
Unzip the dataset:

    unzip fer2013.zip -d ./data

Your data will be stored in the ./data folder. You can change this path as needed.

## 4. Additional Resources

1. Vision Transformer Documentation
2. Pytorch Documentation
3. Kaggle API Documentation