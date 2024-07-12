
# Intruder Detecting System

The Security Alarm System Project using Ultralytics YOLOv8 enhances security with advanced computer vision capabilities. YOLOv8, a state-of-the-art object detection model by Ultralytics, enables the system to promptly identify and respond to potential threats in real-time. This project offers several key advantages:

- **Real-time Detection**: The efficiency of YOLOv8 allows the Security Alarm System to detect and respond to security incidents instantly, minimizing response time.
- **Accuracy**: Known for its precise object detection, YOLOv8 reduces false positives, thereby increasing the reliability of the security alarm system.
- **Integration Capabilities**: The project can seamlessly integrate with existing security infrastructure, providing an upgraded layer of intelligent surveillance.A brief description of what this project does and who it's for

Have Used YOLOv8n a pretrained model for Intruder Detection

## Code

Set up the parameters of the message inside Email_settings.py

Navigate to App Password Generator, designate an app name such as "security project," and obtain a 16-digit password. Copy this password and paste it into the designated password field as instructed.

password = ""

from_email = ""  # must match the email used to generate the password

to_email = ""  # receiver email
## Deployment

To deploy this project run

```bash
  python -u "security_system.py"
```


## FAQ

#### How does Ultralytics YOLOv8 improve the accuracy of a security alarm system?

Ultralytics YOLOv8 enhances security alarm systems by providing high-accuracy, real-time object detection. Its advanced algorithms greatly reduce false positives, ensuring the system responds only to genuine threats. This increased reliability can be seamlessly integrated with existing security infrastructure, elevating the overall quality of surveillance.

#### What sets Ultralytics YOLOv8 apart from other object detection models like Faster R-CNN or SSD?

Ultralytics YOLOv8 excels in real-time detection and higher accuracy. Its unique architecture enables it to process images much faster without sacrificing precision, making it ideal for time-sensitive applications such as security alarm systems. For a detailed comparison of object detection models, you can explore guide https://docs.ultralytics.com/models/.


## Screenshots

![Detection](![Screenshot 2024-07-12 125817](https://github.com/user-attachments/assets/c1b2225f-d31b-49a1-9352-f51e8fa94c5c))

![Generated Alert](https://drive.google.com/file/d/1-7iL_RHMt4DsqKjPOB-YJxms2X-zVu0F/view?usp=sharing)

