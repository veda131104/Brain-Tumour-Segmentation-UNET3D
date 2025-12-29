# Brain-Tumour-Segmentation-UNET3D
## Introduction
Brain tumours happen when cells grow out of control in or around the brain. Detecting and accurately mapping these tumours is critical for diagnosis, treatment planning, and monitoring a patient’s recovery over time. Medical imaging, especially magnetic resonance imaging (MRI), plays a key role in identifying tumor location and structure, but manual analysis of MRI scans is time-consuming and depends heavily on expert interpretation. This project uses deep learning to automatically segment brain tumors from MRI scans. Specifically, a 3D U-Net–based deep learning architecture is trained on multimodal MRI data to identify and classify different tumor sub-regions.

## Model Architecture
The proposed segmentation model is based on a **3D U-Net architecture**, designed specifically for volumetric medical image analysis.

<img width="1388" height="508" alt="image" src="https://github.com/user-attachments/assets/d74bb8b7-251e-458f-93a1-852fc4ace993" />

### Why 3D U-Net?
- **Capturing Spatial Context:**
Unlike 2D models, 3D U-Net captures contextual information across all three spatial dimensions, which is critical for understanding tumour structure and continuity in MRI volumes.
- **Handling Volumetric Data:**
MRI scans are inherently volumetric. The 3D convolutional operations preserve spatial coherence and reduce information loss during feature extraction.
- **Complexity of Brain Tumour Features:**
Brain tumours vary in size, shape, and intensity.

## Results and Performance

<img width="1580" height="1980" alt="image" src="https://github.com/user-attachments/assets/3dc2f1d8-6e71-470f-ac14-888c1b3e6a27" />

The figure above illustrates the training and validation performance of the 3D U-Net model across multiple epochs. The loss curves show a steady decline for both training and validation phases, indicating stable convergence and effective learning. The close alignment between the two curves suggests minimal overfitting and good generalization to unseen data.


| Metric     | Score (%) |
|------------|-----------|
| Accuracy   | 99.85     |
| Precision  | 82.48     |
| Recall     | 85.92     |
| F1 Score   | 84.17     |

The results indicate strong segmentation performance, with high accuracy and balanced precision–recall values, demonstrating the model’s ability to reliably identify brain tumour regions from MRI scans.


## Citation

If you use this work, model architecture, or experimental results in your research or projects, please cite the following paper:

```bibtex
@INPROCEEDINGS{10725309,
  author={Oviya, I R and Vishnu, S and Anusha, Janani Srinivasan and Chatiyode, Veda and Priyanga, S and Charan, K. Kumara Siva},
  booktitle={2024 15th International Conference on Computing Communication and Networking Technologies (ICCCNT)}, 
  title={Enhanced Brain Tumor Segmentation using UNet3D: A Deep Learning Perspective}, 
  year={2024},
  pages={1--7},
  keywords={Deep learning; Image segmentation; Magnetic resonance imaging; Brain tumors; Multimodal MRI; U-Net},
  doi={10.1109/ICCCNT61001.2024.10725309}
}
```
