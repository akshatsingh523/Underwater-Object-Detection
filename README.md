# UNDERWATER-OBJECT-DETECTION-USING-YOLO-V8
Here are the Results for the Project-https://drive.google.com/drive/folders/128h96UMGNFU2mOoAvCtZNoflB_DxjD6C?usp=sharing

Project Title: Pond Waste Detection using YOLOv8

Use Case:
The project aims to address the issue of environmental pollution in local ponds by developing an automated waste detection system. This system will help in identifying and categorizing both non-biodegradable and biodegradable objects in pond environments, enabling better management and cleanup efforts.

Problem Statement:
Local ponds are vulnerable to pollution caused by the indiscriminate disposal of waste materials. To effectively address this problem, there is a need for a reliable and automated waste detection system that can identify and classify different types of waste in pond environments. Traditional manual cleanup efforts are time-consuming and often insufficient in tackling the scale of pollution. Therefore, this project seeks to create a solution that utilizes computer vision and deep learning techniques to automate the detection and categorization of waste objects in pond areas.

Project Details:

Data Collection:

Gathered data by physically visiting a local pond.
Created a dataset comprising both non-biodegradable and biodegradable objects.
Recorded 10 videos, each lasting 10 minutes, to capture a wide range of waste scenarios.
Extracted frames from videos using CV2, resulting in 115 frames.
Data Preprocessing:

Utilized CV2 to remove duplicate frames, refining the dataset and reducing redundancy.
Ensured that the dataset is well-prepared for training.
Image Annotation:

Employed Roboflow for image annotation, enhancing data quality by labeling objects in the images.
Accurately annotated objects to train the model effectively.
Data Splitting:

Divided the annotated images into training, testing, and validation sets to facilitate model training, evaluation, and testing.
Model Implementation:

Implemented YOLOv8, a state-of-the-art object detection algorithm, for waste detection in pond environments.
Adjusted hyperparameters to optimize the model's performance.
Increased the number of training epochs to 100 to ensure better convergence and improved accuracy.
Results:

Achieved a Mean Average Precision (mAP) score of 84.109% at a 50% confidence level, indicating the model's ability to detect waste objects reliably.
Attained a mAP score of 55.231% at a 95% confidence level, demonstrating the model's robustness in detecting waste even with higher confidence thresholds.

Results from Yolo v4:
![image](https://github.com/akshatsingh523/Underwater-Object-Detection/assets/49590899/d12574e1-49ad-4716-931c-a4480c8c3a15)

Results from Yolo v5 :
![image](https://github.com/akshatsingh523/Underwater-Object-Detection/assets/49590899/1123e6a0-3613-4635-a426-3bc8652964c0)

Results from Yolo v7:
![WhatsApp Image 2023-12-18 at 16 50 54_2a9dd8d7](https://github.com/akshatsingh523/Underwater-Object-Detection/assets/49590899/f7629346-0d3b-4bd6-8619-92347b86e9f0)

Results from Yolo v8:
![image](https://github.com/akshatsingh523/Underwater-Object-Detection/assets/49590899/6f4a6942-98e8-42b9-8efc-ae23f65f1e9a)

final results comparision :
![image](https://github.com/akshatsingh523/Underwater-Object-Detection/assets/49590899/b7a108cd-db46-4acd-950f-d2c3f1afc235)





