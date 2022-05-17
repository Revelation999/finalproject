# finalproject
Author: Zhiyuan Huang

## How to Run:
Step 1: Open the notebook in Google Colab with GPU runtime type

Step 2: Install awscli on your local device

Step 2: Download training data with the command `aws s3 cp s3://stoic2021-training/ /path/to/destination/ --recursive --no-sign-request`

Step 3: Upload the training data to Google Drive and mount it with the first code block of the Colab notebook

Step 4: Install SimpleITK and timm via the second and third code block

Step 5: Execute through the rest of the code blocks to obtain the trained model
