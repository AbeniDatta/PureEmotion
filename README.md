# PureEmotion - A Real-Time Expression Analysis System

1. Developed a real-time facial emotion detection system using PyTorch with ~65.62% accuracy, leveraging Mediapipe for facial landmark extraction to reduce computational overhead.
2. Fine-tuned ResNet-18 on FER-2013 by unfreezing all four residual layers plus the fully-connected head, thus improving accuracy by ~30% over an initial FC-only approach.
3. Addressed lighting inconsistencies and occlusions using OpenCV by applying histogram equalization and adaptive thresholding, ensuring ~10% reduction in classification errors. (remove these, then run and check this number on another notebook).

## Demo Video:
To test robustness, I selected a background with uneven lighting and wore my glasses to introduce occlusion challenges. The file is uploaded under the name "Demo Video".


