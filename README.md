1. The general pipeline for this project is to first have the default YOLO model trained on a animal dataset such as the kaggle one mentioned here: https://www.kaggle.com/api/v1/datasets/download/iamsouravbanerjee/animal-image
2. This project uses the dataset provided above, both curating is and reformatted to match the yaml file requirement and directoy design that ultralytics YOLO models require for further training
3. If you are running this code on your own as well, please remember that the paths are fixed and not dynamic, please adjust accordingly

I have also included my trained version of the yolo weights here to avoid the pain in the head of training the yolo model from scratch
