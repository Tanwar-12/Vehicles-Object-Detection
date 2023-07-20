# Vehicles-Object-Detection



### Overview : The goal of this project is to detect and localize vehicles in images or videos.

### 📁 Dataset Used :  https://public.roboflow.ai/object-detection/undefined
**The dataset consists of 5 classes:**
- Bus
- Truck
- Car
- Traffic signal
- Truck
  # Workflow:
  ## Data Preparation:
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.
  ![train folders](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/69b19a8e-2f81-4d9b-a762-ffa73ac59be1)
## Steps to use Yolov5:
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.

 ## Steps Before Training Custom Dataset:
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:

 1. Training and Validation file path
 2. Number of classes and Class names.

  ## Training YOLOV5 Model
* Set images size 640 with batch of 8.
* Train model around 600 epochs .
* Visualise the training metrics with the help of tensorboard.

 ## Testing Images Using Test Data
 
![download (14)](https://github.com/Tanwar-12/Vehicles-Object-Detection/assets/110081008/646c06eb-98b6-4dd7-a62e-e04ca6f0ac3a)

![download (16)](https://github.com/Tanwar-12/Vehicles-Object-Detection/assets/110081008/40630872-89f6-4cc0-abf4-907ad69987aa)


![download (15)](https://github.com/Tanwar-12/Vehicles-Object-Detection/assets/110081008/07065413-f809-45e1-8e27-19e0a69f447d)

## Testing Video Demo






