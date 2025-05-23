1. Create an Account on Google Colab

If you don’t already have an account, sign up for Google Colab using your Gmail ID.

Access the Colab platform via https://colab.research.google.com.


2. Access the Colab Notebook

Open the provided Colab notebook that contains the source code for the project.

Ensure that all necessary code cells are included and properly structured for the tasks.


3. Upload Required Files

Navigate to the Colab directory (file panel on the left side).

Upload the following files:

Dataset: Include all the image data used for detection.

best.pt: The trained YOLOv8 model weights file.

Audio Files: Include any audio notification files needed for alerts.


Ensure all files are organized within a single folder (e.g., programs) for easy referencing in the code.


4. Execute the Code (Except Training)

Skip the training code block since the model has already been trained.

Run the other code blocks in sequence to set up the environment, load the model, and prepare the dataset for inference.

Ensure all dependencies are installed correctly, such as YOLOv8, torch, and opencv-python.


5. Perform Inference and Verify Outputs

Run the inference code to test the model’s performance.

Upload test videos or images to the Colab directory for verification.

Check the detection results, which include bounding boxes and alerts for detected gestures, crimes, or emergencies.

Verify the output logs and results visually to ensure accuracy and functionality.