# Advanced Automated Segmentation Model for Brain Tumors using Modified 3D U-Net
The project involved the development and implementation of a sophisticated automated segmentation model specifically designed for brain tumor analysis.
By utilizing both the original **3D U-Net** architecture and a modified version of the model, we trained the system to accurately segment brain tumors. The model's performance was evaluated using reliable evaluation metrics such as Intersection over Union (IoU) score and Dice coefficient. 


# Dataset
BRATS 2020 dataset was used for this project. 
The official link : https://www.med.upenn.edu/cbica/brats2020/data.html


***Image Format*** : *.nii
<br>
***Scan Types*** : 
- *Native (T1)*
- *Post-contrast T1-weighted (T1ce)*
- *T2-weighted (T2)*
- *T2 Fluid Attenuated Inversion 
Recovery (T2-FLAIR) volumes*
- *Ground Truth*

**Dataset Samples:
![sample_image](https://github.com/phreak1703007/Segmentation/assets/62479964/bf03e8dd-c3a1-4fd7-8998-06bce1a0a93c)
# 3D U-Net Architecture: 
<br>
![3d u net](https://github.com/phreak1703007/Segmentation/assets/62479964/c7a2863d-91c9-4c7c-a9f8-bb9e2bb1c814)


# Results: 
The performance of the model was rigorously evaluated using the **IoU (Intersection over Union) score** and **Dice coefficient/F1-Score** as reliable evaluation metrics. 
*Accuracy*
![accuracy](https://github.com/phreak1703007/Segmentation/assets/62479964/8a5353b3-b948-4d82-8959-c87b04bbf9d9)
<br>
*Iou Score*
![Iou_score](https://github.com/phreak1703007/Segmentation/assets/62479964/451bad19-f4a1-478f-9d14-6f58bc10cbbe)
<br>
*DSC/F1-Score*
![f1](https://github.com/phreak1703007/Segmentation/assets/62479964/a9702bff-b9c7-4743-a6e5-fc061412d47d)



