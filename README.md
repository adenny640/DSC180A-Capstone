# DSC180A-Capstone

Our dataset is generated via the imageGen.py script, which requires the user to have a Google Cloud account with access to the Google Street View API. In order to use the script, users will need to have a .env file which will store the Google API key and their secret to generate digital signatures for the API calls. 

The script generates 150 images of 10 structures where each structures has images as follows.
Images are taken from 5 different view points, and each image is taken at 3 different zoom levels, leading to 15 images per structure. 


.env file structure is as follows:

APIKEY= xxxxxxxxx
SECRET= xxxxxxxxx