Vehicle Detection using Transformer based deep models (DETR)

## Dataset

Dataset : https://drive.google.com/file/d/1uQ2tJvnsQQdTf-44S5vT4dJRQOpfEjL0/view?usp=drive_link
The dataset includes 4829 images (4200 for Training, 425 for validation and 204 for Testing). The dataset has seven different categories AutoRikshaw', 'Bike', 'Bus', 'Car', 'Maxi Cab', 'Mini Truck', 'Truck.

### Fine tuning

Open the Train_detr.ipynb in google colab. DETR ResNet 50 and ResNet 101 pretrained model weights are used for fine tuning the custom dataset.

Download the trained model weights for ResNet50 and ResNet101 in https://drive.google.com/file/d/1J4c6iCXG4sLz1751lSQe0CoKIqUd7Eyn/view?usp=drive_link, https://drive.google.com/file/d/14fJLmqzoOD7CXk83-Pq07ZIbLUssnkQH/view?usp=drive_link correspondingly.

#### Inference

open the Test_detr.ipynb in colab.
Load the weights using the above trained model weights, to detect the objects in the test data.
Test dataset predictions output are saved in test_output-20230809T160424Z-001.zip
