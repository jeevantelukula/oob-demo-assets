# OOB Demo Assets

This repository serves as a collection of open-source pre-trained deep learning models. These models are currently used by the Yocto SDK for TI processors for DL inferencing on Cortex-A ARM cores.

## Models Included

### Model 1: regnetx-200mf.onnx
- Description: A pre-trained deep learning model in the ONNX (Open Neural Network Exchange) format, optimized for efficient and scalable deep learning tasks with a computational complexity of 200MFLOPs.
- Source: [GitHub - RegNet](https://github.com/facebookresearch/pycls)
- Research Paper: [Designing Network Design Spaces](https://arxiv.org/abs/2003.13678)

### Model 2: ssd_mobilenet_v2_coco.tflite
- Description: A pre-trained TensorFlow Lite model that combines the Single Shot MultiBox Detector (SSD) with the MobileNetV2 architecture for efficient object detection on mobile and embedded devices.
- Source: [GitHub - ssd_mobilenet_v2_coco](https://github.com/tensorflow/models/tree/master/research/object_detection)
- Research Paper: [MobileNetV2: Inverted Residuals and Linear Bottlenecks](https://arxiv.org/abs/1801.04381)

### Model 3: yamnet_audio_classification.tflite
- Description: A pre-trained TensorFlow Lite model designed for audio event classification, based on the YamNet architecture.
- Source: [GitHub - YamNet](https://github.com/tensorflow/models/tree/master/research/audioset/yamnet)

### Model 4: en_v5.onnx
- Description: A pre-trained English Speech-to-Text (STT) model in ONNX format, designed for efficient CPU-based inference on edge and embedded devices.
- Source: [GitHub - Silero Models](https://github.com/snakers4/silero-models)

## Usage
To use these models with the Yocto SDK for TI processors, follow the instructions provided in the [Yocto SDK documentation](https://texasinstruments.github.io/processor-sdk-doc/)

**Note:** These models can be used on any other platforms and are not tied to TI SoCs.

## References
- [Designing Network Design Spaces](https://arxiv.org/abs/2003.13678) - Ilija Radosavovic, Raj Prateek Kosaraju, Ross Girshick, Kaiming He, Piotr Dollár
- [MobileNetV2: Inverted Residuals and Linear Bottlenecks](https://arxiv.org/abs/1801.04381) - Mark Sandler, Andrew Howard, Menglong Zhu, Andrey Zhmoginov, Liang-Chieh Chen
- [YamNet: A lightweight deep learning model for audio event classification](https://github.com/tensorflow/docs/blob/master/site/en/hub/tutorials/yamnet.ipynb) - The TensorFlow Hub Authors
- [Silero Models: pre-trained speech-to-text and text-to-speech models for multiple languages](https://github.com/snakers4/silero-models) - Alexander Veysov et al.

## License
This repository is licensed under the TI-TFL License. See the [LICENSE](LICENSE) file for more information.

**Disclaimer:** Even though the repository is licensed under TI-TFL, each model in the repository comes with its own LICENSE. Please refer to the References section for more details on the license of each model.
