# Real-Time Traffic Monitoring System  

## Overview  
This project focuses on developing a Real-Time Traffic Monitoring System that detects vehicles crossing a designated red line. It integrates object detection capabilities using the YOLO model with OpenCV and TensorFlow. The system processes high-resolution traffic videos (60 FPS) in real time, providing visual overlays and maintaining data logs for analysis.  


## Key Features  
- *Real-Time Vehicle Detection*:  
  Utilizes the YOLO model to identify vehicles in high-resolution videos.  
- *Violation Detection*:  
  Flags vehicles that cross a specified red line.  
- *Visual Overlays*:  
  Provides bounding boxes around detected vehicles and highlights violations.  
- *Data Logging*:  
  Records timestamped logs of red-line crossing events and vehicle counts.  
- *High-Performance Processing*:  
  Handles 60 FPS videos efficiently using OpenCV and TensorFlow.  



## Tech Stack  
- *Programming Language*: Python  
- *Libraries*:  
  - OpenCV: For video processing and visualization  
  - TensorFlow: For model integration  
  - YOLO: For object detection  
- *Platform*: Google Colab (for development and testing)  


## Dataset  
- *Source*: Public datasets from Kaggle or Google Datasets.  
- *Requirements*:  
  - Traffic videos/images in high resolution.  
  - Dataset examples include urban traffic monitoring scenarios.  
- *Example Datasets*:  
  - [Highway Traffic Dataset on Kaggle](https://www.kaggle.com/datasets)  
  - [Urban Traffic Monitoring Dataset on Google Datasets](https://datasetsearch.research.google.com/)  


### 1. Clone the Repository  
```bash  
git clone https://github.com/gayathribaby05/Real-Time-Traffic-Monitoring-System.git
cd real-time-traffic-monitoring
```
### Run the following commands
```bash
pip install torch torchvision opencv-python pandas
```

###  Screenshots
https://github.com/gayathribaby05/Real-Time-Traffic-Monitoring-System/blob/f84730b79139dd2848709e37cf0dbdcc5d7b3c8b/ss1.png

https://github.com/gayathribaby05/Real-Time-Traffic-Monitoring-System/blob/27418ed4346cdd9e377a2017a4aeb926c9ca17e0/ss2.png





