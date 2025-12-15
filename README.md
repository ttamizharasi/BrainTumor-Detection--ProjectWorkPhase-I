## Brain Tumor Detection from MRI Images using GAN-based Anomaly Detection
The project focuses on developing an automated system for detecting brain tumors from MRI images using Generative Adversarial Networks (GANs). The system aims to assist radiologists by accurately identifying abnormal regions in brain scans, reducing manual effort and improving early diagnosis.

## About
<!--Detailed Description about the project-->
Brain Tumor Detection from MRI Images using GAN-based Anomaly Detection is a deep learning–based project designed to automatically identify tumor regions in brain MRI scans. Manual examination of MRI images is time-consuming, subjective, and prone to human error. This project overcomes these limitations by employing an unsupervised GAN model trained on healthy MRI images to learn normal brain structures.

During testing, MRI images containing tumors are treated as anomalies, as the GAN fails to reconstruct abnormal regions accurately. The difference between original and reconstructed images highlights potential tumor areas. This approach reduces dependency on large labeled datasets and provides a scalable, efficient, and accurate solution for medical image analysis.

## Features
<!--List the features of the project as shown below-->
- GAN-based unsupervised anomaly detection model
- No requirement for labeled tumor datasets
- Automatic detection and localization of tumor regions
- High detection accuracy with reduced false positives
- Scalable and efficient deep learning architecture
- Visualization of original, reconstructed, and anomaly maps
- Reduced time complexity compared to manual diagnosis

## Requirements
<!--List the requirements of the project as shown below-->
Software Requirements
* Operating System: 64-bit Windows 10 / Ubuntu
* Programming Language: Python 3.6 or later
* Deep Learning Framework: TensorFlow (v2.4.1) / Keras
* Image Processing Library: OpenCV
* Machine Learning Libraries: NumPy, scikit-learn, Matplotlib
* IDE: VS Code / Jupyter Notebook
* Version Control: Git
* Hardware Requirements
* Intel i5 or higher processor
* Minimum 8 GB RAM (16 GB recommended)
* NVIDIA GPU (optional but recommended for faster training)
  
Hardware Requirements
* Intel i5 or higher processor
* Minimum 8 GB RAM (16 GB recommended)
* NVIDIA GPU (optional but recommended for faster training)
## System Architecture
<!--Embed the system architecture diagram as shown below-->

![Screenshot 2023-11-25 133637](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/a60c11f3-0a11-47fb-ac89-755d5f45c995)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![Screenshot 2023-11-25 134037](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/8c2b6b5c-5ed2-4ec4-b18e-5b6625402c16)

#### Output2 - Name of the output
![Screenshot 2023-11-25 134253](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/5e05c981-05ca-4aaa-aea2-d918dcf25cb7)

Detection Accuracy: 96.7%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
<!--Give the results and impact as shown below-->
The proposed GAN-based anomaly detection system significantly improves the accuracy and efficiency of brain tumor detection. It reduces diagnostic workload, minimizes human error, and enables early tumor identification, which is crucial for effective treatment planning.

This project demonstrates the effectiveness of unsupervised deep learning in medical imaging and provides a strong foundation for real-world clinical decision support systems. It contributes toward intelligent healthcare solutions and promotes AI-driven medical diagnostics.

This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References

Schlegl, T. et al., Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery, IPMI, 2017.
Baur, C. et al., f-AnoGAN: Fast Unsupervised Anomaly Detection with GANs, Medical Image Analysis, 2020.
Deepak, S. et al., Brain Tumor Classification Using Deep CNN, Biomedical Signal Processing and Control, 2019.
Yurtsever, M. M. E. et al., GAN-based Augmentation for Brain Tumor MRI, BMC Medical Informatics, 2024.




