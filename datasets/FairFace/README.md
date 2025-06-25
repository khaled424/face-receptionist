
# FairFace Dataset

This folder contains two versions of the FairFace dataset with different cropping margins.

- `margin025/`: standard tight crop around the face.
- `margin125/`: looser crop, showing more context.

Each folder contains `train/` and `val/` subfolders with labeled images for training and evaluation.



- Format: train/val images, `train_labels.csv`, `val_labels.csv`
- Used for: diverse training across ethnicities