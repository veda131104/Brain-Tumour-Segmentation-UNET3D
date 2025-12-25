# Brain-Tumour-Segmentation-UNET3D
## Introduction
Brain tumors happen when cells grow out of control in or around the brain. This project uses AI (Deep Learning) to help doctors find and map these tumors more accurately using MRI scans. By getting the mapping right, doctors can plan better treatments and track how a patient is recovering. We built a specialized AI model called a **U-Net**. To make it more powerful, we added:
* **Multiple Views:** It looks at four different types of MRI scans (T1, T2, T1c, and FLAIR) at the same time.
* **Attention & Residual Layers:** These help the AI focus on the most important parts of the image and learn faster.
* **Smart Analysis:** The model doesn't just find the tumor; it also helps tell the difference between a tumor coming back and a fake alarm (pseudoprogression).
