# High Dynamic Range Modulo Imaging for Robust Object Detection in Autonomous Driving.
[![demo-online](https://img.shields.io/badge/demo-online-success?style=flat-square)]([https://tu-demo-url.com](https://huggingface.co/spaces/kebincontreras/Object_Detection_Modulo_Camera))

Object detection precision is crucial for ensuring the safety and efficacy of autonomous driving systems. The quality of acquired images directly influences the ability of autonomous driving systems to correctly recognize and respond to other vehicles, pedestrians, and obstacles in real-time. However, real environments present extreme variations in lighting, causing saturation problems and resulting in the loss of crucial details for detection. Traditionally, High Dynamic Range (HDR) images have been preferred for their ability to capture a broad spectrum of light intensities, but the need for multiple captures to construct HDR images is inefficient for real-time applications in autonomous vehicles. To address these issues, this work introduces the use of modulo sensors for robust object detection. The modulo sensor allows pixels to `reset/wrap' upon reaching saturation level by acquiring an irradiance encoding image which can then be recovered using unwrapping algorithms. The applied reconstruction techniques enable HDR recovery of color intensity and image details, ensuring better visual quality even under extreme lighting conditions at the cost of extra time. Experiments with the YOLOv10 model demonstrate that images processed using modulo images achieve performance comparable to HDR images and significantly surpass saturated images in terms of object detection accuracy. Moreover, the proposed modulo imaging step combined with HDR image reconstruction is shorter than the time required for conventional HDR image acquisition.
