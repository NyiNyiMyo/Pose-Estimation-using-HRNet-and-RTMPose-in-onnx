<div align="center">
    <h1>Pose Estimation using HRNet and RTMPose <br/> in onnx </h1>
</div>

[![python](https://img.shields.io/badge/Python-3.12-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![pytorch](https://img.shields.io/badge/PyTorch-2.8.0-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
![Static Badge](https://img.shields.io/badge/Pose-Estimation-cyan)
![Static Badge](https://img.shields.io/badge/ONNX-lightgray)

<div align="center">
    <h3>HRNet Pose Estimation </h3>
</div>

<img src="https://github.com/user-attachments/assets/22e6b7bc-6756-4e77-a080-01629e9f0c1a" width="810" height="600">

<div align="center">
    <h3>RTMPose Pose Estimation </h3>
</div>

<img src="https://github.com/user-attachments/assets/9095ba5e-4df0-48f6-ba84-39142c8b0eae" width="270" height="600"> <img src="https://github.com/user-attachments/assets/4c58ff2d-4c8a-4f8c-bfb5-7a9421159099" width="260" height="600"> <img src="https://github.com/user-attachments/assets/d5e42cbf-7b45-4fe7-ba47-92d2358cd835" width="280" height="600">

<img src="https://github.com/user-attachments/assets/276af5df-2da5-4e8c-8389-ec3aa8a501a6" width="570" height="600"> <img src="https://github.com/user-attachments/assets/600291e0-91e7-4f63-bfca-81847c263775" width="240" height="600">

---

## 🏗️ Methodology

- 🤸‍♂️ Pose Estimation Model1: **hrnet_coco_w48_384x288.onnx**
- 🤸‍♂️ Type: **Top-down**
- 🤸‍♂️ Object Detection Model: **v9-m_mit.onnx**
- 🤸‍♂️ Framework: **onnxruntime**
- 🤸‍♂️ Pose Estimation Model2: **rtmpose-l-coco-body.onnx**
- 🤸‍♂️ Pose Estimation Model3: **rtmpose-l-halpe26-body.onnx**
- 🤸‍♂️ Pose Estimation Model4: **rtmpose-l-humanart-body.onnx**
- 🤸‍♂️ Type: **Top-down**
- 🤸‍♂️ Object Detection Model: **ssdlite320_mobilenet_v3_large**
- 🤸‍♂️ Framework: **PyTorch + onnxruntime**
- 🤸‍♂️ Pose Estimation Model5: **rtmpose-l-ucoco-body.onnx**
- 🤸‍♂️ Type: **Top-down**
- 🤸‍♂️ Face Detection Model: **yolov11n-face.onnx**
- 🤸‍♂️ Framework: **PyTorch + onnxruntime**

---

## ⭐ Acknowledgements

- onnxruntime
- ssdlite320 powered by `torchvision.models`

---
