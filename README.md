# Perform Object Detection YOLOv8

This project demonstrates the use of the YOLOv8 (You Only Look Once version 8) deep learning model for real-time object detection, specifically focusing on identifying birds within an image. The model is pre-trained on the COCO dataset, which supports detection of 80 common object categories.

The image used in this task, birds.jpg, is processed to:

Detect and label all objects with a confidence level greater than 50%.
Filter the results to display only objects classified as "bird" with a confidence level greater than 50%.
Visually present three output versions of the image:
The original image (for reference)
An image showing all high-confidence detections
An image showing only high-confidence bird detections

---
 ### Recommendations / Enhancements

| Suggestion                        | Benefit                                              |
| --------------------------------- | ---------------------------------------------------- |
| Add object count                  | Helps quantify detection results                     |
| Include legend                    | Clarifies color coding for boxes                     |
| Try `yolov8s.pt`                  | Improved accuracy with a slight performance tradeoff |
| Save plots via Matplotlib         | Export a side-by-side plot as a PNG/JPEG             |
| Add function-based implementation | For better modularity and reuse                      |


### Purpose and Learning Outcomes

This project demonstrates:

Application of pretrained YOLO models for visual recognition tasks.
Practical use of confidence-based filtering in computer vision.
Image annotation using OpenCV.
Data visualization and result presentation using Python.
Clean, modular coding with readable comments and structure.
