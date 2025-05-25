# ml-image-recognition

This project uses Python 3.10 to create and test an image recognition model trained using Google's Teachable Machine.

## Project Structure

1. **`datacollection.py`** – Script to collect and save training data (images).  
2. **Teachable Machine** – Used to train and export the model as a `.h5` file.  
3. **`test.py`** – Script to load the `.h5` model and test it on new input.

## Steps

1- Create a virtual environment and install dependencies:


    python -m venv venv
    source venv/bin/activate      # On Windows: venv\Scripts\activate
    pip install -r requirements.txt
    


2. Create Dataset and Train Your Own Model (Optional)
    If you want to create your own dataset and train your own model (optional), run the data collection script to save images locally:
    python datacollection.py
    Next, go to Teachable Machine, upload your dataset, train your model, and export it in .h5 format.
    Once you have your .h5 model file, place it in the project directory and run the test script to evaluate the model:



3. python test.py
Notes
    The model is trained externally using Google's Teachable Machine and tested locally using Python.
    You can use the provided dataset and model or create your own.
    yaml


