# U-Net Pet Segmentation

Binary semantic segmentation of pets using a U-Net trained on the Oxford-IIIT Pet Dataset.

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

## Results
- **Accuracy:** 87%
- **Mean IoU:** 0.61
- **Dataset:** Oxford-IIIT Pet (3,680 train / 3,669 test)
- **Training:** 25 epochs with data augmentation on T4 GPU

## Training Curves
![Training Curves](results/training_curves.png)

## Validation Results
![Val 1](results/validation/val_result_v2_0.png)
![Val 2](results/validation/val_result_v2_1.png)

## Custom Image Results
![Outdoor](results/custom/custom_outdoor.png)
![Indoor](results/custom/custom_room.png)
