# Nails Segmentation with U-Net

This project explores **binary image segmentation** for fingernails using a compact **U-Net** model implemented in TensorFlow/Keras.

## Project Overview
- **Task:** Segment fingernails (foreground) from background in hand images.
- **Model:** U-Net with skip connections, trained from scratch.
- **Loss:** Custom soft **Dice loss** (foreground channel).
- **Metrics:** Dice coefficient and IoU, computed during training and on the test data for evaluation.
- **Data Augmentation:** Simple horizontal/vertical flips to improve generalization.
