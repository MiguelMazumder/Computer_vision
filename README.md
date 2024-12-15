### YOLO Animal Detection Project
This project utilizes YOLO (You Only Look Once) to detect and classify animals in images and videos. It includes custom-trained YOLO weights, a curated dataset, and functionality to process videos, identify specific animals, and skip to specific frames where the animals are detected.
## Project Structure
The general pipeline for this project is to first have the default YOLO model trained on a animal dataset such as the kaggle one mentioned here: https://www.kaggle.com/api/v1/datasets/download/iamsouravbanerjee/animal-image

1. This project uses the dataset provided above, both curating is and reformatted to match the yaml file requirement and directoy design that ultralytics YOLO models require for further training. The yolodataset folder contains the images, labels, and yaml file for the dataset path
2. YOLO Weights (last.pt and best.pt) (These are the wieghts of my trained yolo model)
3. If you are running this code on your own as well, please remember that the paths are fixed and not dynamic, please adjust accordingly
4. animal_trained.ipynb is responsible for training the YOLO model to look at 90 different animals catagories
5. skip_to_animal.ipynb is responsible for the processing of a video and allows skipping to specific frames where an animal is detected

