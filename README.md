# U-Net Pet Segmentation

Binary semantic segmentation of pets using a U-Net trained on the Oxford-IIIT Pet Dataset.

## Results
- **Accuracy:** 87%
- **Mean IoU:** 0.61
- **Dataset:** Oxford-IIIT Pet (3,680 train / 3,669 test)

## Training Curves
![Training Curves](results/training_curves.png)

## Validation Results
![Val 1](results/validation/val_result_v2_0.png)
![Val 2](results/validation/val_result_v2_1.png)

## Custom Image Results
![Outdoor](results/custom/custom_outdoor.png)
![Indoor](results/custom/custom_room.png)

## Tech Stack
- TensorFlow/Keras
- Google Colab (T4 GPU)
- Data augmentation (flips, brightness)
- 25 epochs
