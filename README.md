# Analysis-of-Brain-Tumor-Segmentation-Leveraging-KNN-SVM-Random-Forest
This repository contains a dataset of T1-weighted contrast-enhanced brain MRI images for brain tumor analysis from 233 patients. It includes images of three types of brain tumors.

## Dataset Description

**Total Images:** 3064
**Patients:** 233
**Image Type:** Grayscale
**Image Size:** 512x512 pixels


**Tumor Types:**
* **Meningioma:** 708 slices
* **Glioma:** 1426 slices
* **Pituitary Tumor:** 930 slices

## Data Example

Here are some examples from dataset:
![Meningioma Example](https://github.com/user-attachments/assets/f6ed9af3-015c-4522-be39-f00916b9fdc0)

## Preprocessing

* Remove noise outside the skull
![Screenshot 2024-08-05 114630](https://github.com/user-attachments/assets/a71a0857-016f-4a4d-b96a-a7d22f0012dc)

* Contrast Enhancment
![Screenshot 2024-08-05 114745](https://github.com/user-attachments/assets/9500a753-08a1-4bc7-8597-507db8ca6d68)

  
* Skull Stripping
  ![Screenshot 2024-08-05 114915](https://github.com/user-attachments/assets/7266096d-da41-4008-8ca0-19ababbc3934)

* HOG Descriptors to extract features from images

## Best Model Results

![Screenshot 2024-08-05 115215](https://github.com/user-attachments/assets/41752318-fd62-4557-a7c2-8fbedb758b9c)


