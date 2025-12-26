# Brain-Tumour-Segmentation-UNET3D
## Introduction
Brain tumors happen when cells grow out of control in or around the brain. Detecting and accurately mapping these tumors is critical for diagnosis, treatment planning, and monitoring a patient’s recovery over time. Medical imaging, especially magnetic resonance imaging (MRI), plays a key role in identifying tumor location and structure, but manual analysis of MRI scans is time-consuming and depends heavily on expert interpretation. This project uses deep learning to automatically segment brain tumors from MRI scans. Specifically, a 3D U-Net–based deep learning architecture is trained on multimodal MRI data to identify and classify different tumor sub-regions.

## Model Architecture
The proposed segmentation model is based on a 3D U-Net architecture, designed specifically for volumetric medical image analysis.
<img width="1388" height="508" alt="image" src="https://github.com/user-attachments/assets/d74bb8b7-251e-458f-93a1-852fc4ace993" />
### Why 3D U-Net?
**Capturing Spatial Context**
Unlike 2D models, 3D U-Net captures contextual information across all three spatial dimensions, which is critical for understanding tumour structure and continuity in MRI volumes.
**Handling Volumetric Data**
MRI scans are inherently volumetric. The 3D convolutional operations preserve spatial coherence and reduce information loss during feature extraction.
**Complexity of Brain Tumour Features**
Brain tumours vary in size, shape, and intensity.


