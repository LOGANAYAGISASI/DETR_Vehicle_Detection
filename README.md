# Detr_Vehicle__Detection
Transformer based detection 

## Dataset

Dataset : https://drive.google.com/file/d/1uQ2tJvnsQQdTf-44S5vT4dJRQOpfEjL0/view?usp=drive_link
dataset was exportred via https://app.roboflow.com/ I download dataset in COCO format.
The dataset includes 4829 images. I have used 4200 images for Training and for testing i have used 204 images.

Open the finetune_detr.ipynb in colab.

Train and test dataset.

Download the trained model weights in https://drive.google.com/file/d/1J4c6iCXG4sLz1751lSQe0CoKIqUd7Eyn/view?usp=drive_link

open the Test_detr.ipynb in colab

Load the weights using the above trained model weights, to detect the objects in the test data.

Run inference on the test set using the model i have have trained

Vehicles are anotated in COCO format.

Save the output images test_output-20230809T160424Z-001.zip
