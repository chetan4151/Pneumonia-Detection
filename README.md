# Pneumonia-Detection

### Original Dataset Link: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia 

### Out of the 5 models that I built, ResNet152V2 model with feature extraction and a custom classifier gave the best accuracy of 89.5%. (For the metrics of all models, please refer to Summary.xlsx)

## All models :

https://drive.google.com/drive/folders/1ERPnwPEJyTjHMkPVoUHPHvcpBCLQUU9d?usp=sharing

### Using the best ResNet152V2 model, I made a web application using Flask, where a user can upload a chest x-ray image and get the diagnosis results.
## Screenshots:
  ![home_page](https://github.com/chetan4151/Pneumonia-Detection/assets/80635460/b8d3d5a8-1464-43b1-867b-565557925ea7)
  ![diagnosis_normal](https://github.com/chetan4151/Pneumonia-Detection/assets/80635460/e5d12c2b-ae4e-4d9c-abb2-498b3d5512db)
  ![diagnosis_pneumonia](https://github.com/chetan4151/Pneumonia-Detection/assets/80635460/cec8cff9-2703-4a17-a200-2c2202a0f2b3)

### To run app on your system, 
- Download all files from this repository
- Download "resnet152v2_feature_extraction_2024-03-13_02_43_42" (model) folder from https://drive.google.com/drive/folders/1ERPnwPEJyTjHMkPVoUHPHvcpBCLQUU9d?usp=sharing and add it in the same directory
- Within this directory, install the dependencies using the command: pip install -r requirements.txt
- run the following command to start the server: flask --app app run


