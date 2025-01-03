# YOLOv11 Model for Construction Site Safety Detection  

## Overview  
This project implements YOLOv11 for real-time detection of Personal Protective Equipment (PPE) compliance on construction sites. The model enhances safety monitoring by detecting and classifying safety equipment and violations in real-time.  

## Key Features  
- **Multi-Class Detection**: Identifies multiple PPE categories including:  
  - Hardhat/No-Hardhat  
  - Mask/No-Mask  
  - Safety Vest/No-Safety Vest  
  - Person, Safety Cone, Machinery, Vehicle  
- **High Performance**: Achieves mAP@50-95: 0.55 and mAP@50: 0.80  
- **Real-Time Processing**: Optimized for efficient on-device inference  
- **Mobile Deployment**: TFLite conversion for Android compatibility  

## Model Performance  
- Hardhat Detection: 97% confidence  
- Safety Vest Detection: 89% confidence  
- Person Detection: 90% confidence  
- Overall Precision: 84.9%  
- Recall: 77.1%  

## Features

- **Object Detection**: Detect multiple classes of PPE in real-time.
- **Performance Metrics Tracking**: Includes loss, precision, recall, and mean Average Precision (mAP).

## Installation

To set up the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/skumbham/PPE-Detection-Using-Yolo11
cd PPE-Detection-Using-Yolo11
pip install -r requirements.txt
```
  
## Dataset Information  
- Total Images: 2801  
  - Training: 2605 images (93%)  
  - Validation: 114 images (4%)  
  - Testing: 82 images (3%)  
- Augmentation techniques applied:  
  - Horizontal flips  
  - Rotations (±12°)  
  - Shear transformations  
  - Brightness/contrast adjustments  
  - Grayscale conversion  

## Video Inference Demo  
Check out our model in action: [Video Demo](https://drive.google.com/file/d/1JSa4mF9R3v4kLJYbzGCsg9ax45cRfCXj/view?usp=drive_link)  

## Future Enhancements  
- Red Zone Detection implementation  
- Dataset expansion for diverse scenarios  
- Predictive analytics for proactive safety measures  

## Contributors  
- Shoumik Reddy Kumbham (skumbham@syr.edu)  
- Likith Kolli (klikhith@syr.edu)  
- Sai Mani Kiran Chatrathi (schatrat@syr.edu)  
- Goutham Sri Vishwesh Bikkumalla (gbikkuma@syr.edu)  

## License  
© 2024 Syracuse University. All rights reserved.  

## References  
- [Ultralytics YOLOv11 Documentation](https://docs.ultralytics.com/models/yolo11/)  
- Syracuse University College of Engineering and Computer Science  
