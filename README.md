# PureEmotion: A Real-Time Expression Analysis System

1. Developed a real-time facial emotion detection system using PyTorch with ~65.62% accuracy, leveraging Mediapipe for facial landmark extraction to reduce computational overhead.
2. Fine-tuned ResNet-18 on FER-2013 by unfreezing all four residual layers plus the fully-connected head, thus improving accuracy by ~30% over an initial FC-only approach.
3. Addressed lighting inconsistencies and occlusions using OpenCV by applying histogram equalization and adaptive thresholding, ensuring ~10% reduction in classification errors.

## Demo Video:
To test robustness, I selected a background with uneven lighting and wore my glasses to introduce occlusion challenges. The file is uploaded under the name "Demo Video.mp4".

P.S.- I have to say it felt very weird recording myself randomly making these faces/expressions 😅


<img width="400" alt="Screenshot 2025-06-02 at 2 15 13 PM" src="https://github.com/user-attachments/assets/539afdc0-d00e-42e2-bacb-a0f67dbd4c9e" />
