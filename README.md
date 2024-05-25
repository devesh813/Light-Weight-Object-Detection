# Light-Weight-Object-Detection
using MobileNet SSd v2, Yolo v5

## Problem Definition
Object detection is essential for applications like surveillance, autonomous driving, and industrial automation 🚗🏭. Traditional models, like complex CNNs and YOLO v5, can be too intensive for real-time use on resource-limited devices 📱. This project explores MobileNet, a lightweight model, for efficient, real-time object detection 🕒🔍. Using depthwise separable convolutions, MobileNet reduces computational load while maintaining performance, ideal for edge devices like smartphones, drones, and embedded systems 🛩️📟. By training MobileNet on annotated datasets, this project aims to develop a robust detection system for various environments, enhancing smart surveillance, industrial automation, and augmented reality 🌐🔧👁️.

Refer Project Report for more detailed analysis.

## To Run
1. You will need a Roboflow API key. If you don't already have a Roboflow account, sign up for a free Roboflow account. Then, retrieve your API key from the Roboflow dashboard. Run the following command to set your API key in your coding environment:

            export ROBOFLOW_API_KEY=<your api key>

2.  pip install inference
3.  pip install inference-gpu
4.  Add Your API Key in both templates "Image/Video" button Link tag 
          Example:  <li> <a href=="https://detect.roboflow.com/?model=small-aerial-object-detection-fwbd7&version=3&api_key=YOUR_API_Key" target="_blank">Video</a></li>
5.  Run flaskapp.py

## Dataset Configeration
We used custom [Indoor-Object-Detection Image Dataset](https://universe.roboflow.com/cued-project/indoor-object-detection-brbbt/dataset/2) from Roboflow to train the model

<img width="572" alt="image" src="https://github.com/devesh813/Light-Weight-Object-Detection/assets/117442634/443e4721-7285-4936-b8ca-c180b784907f">


## mAP Results
<img width="605" alt="image" src="https://github.com/devesh813/Light-Weight-Object-Detection/assets/117442634/f1e0d2ce-af03-4c93-9868-9804cf8eeb97">

<img width="398" alt="image" src="https://github.com/devesh813/Light-Weight-Object-Detection/assets/117442634/fb16d88e-dd2b-451d-a2d5-1c2d4a66742f">


## Sample Output
![12](https://github.com/devesh813/Light-Weight-Object-Detection/assets/117442634/040b1c4d-c701-47a2-9e04-ac4b241ee6be)

![11](https://github.com/devesh813/Light-Weight-Object-Detection/assets/117442634/26af7b2f-4ac5-4478-8a6d-0dec997aa6d3)

![10](https://github.com/devesh813/Light-Weight-Object-Detection/assets/117442634/1567980b-3aa5-4029-867b-3a333d48e668)


## Contributers:
1.[Devesh Borkar](https://github.com/devesh813)

2.Hardik Thakkar

3.Om Bhagat

## Liscence
Distributed under the MIT License. See  for more information.

Please adhere to this project's code of conduct.
