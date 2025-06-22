# Monet Style Transfer with CycleGAN

This project uses a CycleGAN to translate real-world photos into Monet-style paintings. It leverages TensorFlow and the pix2pix architecture to perform artistic style transfer without paired training data.

## ML Models

### CycleGAN with U-Net Generator
CycleGAN enables unpaired image-to-image translation. The model architecture includes:
- Two U-Net generators: Photo → Monet and Monet → Photo
- Two discriminators: Distinguish real from generated images in each domain
- Losses: Adversarial, cycle-consistency, and identity losses

## Files
- `notebooks/`: Jupyter notebook
- `images/`: Model result plots
- `data/`: Training set and test set

## GitHub Repo

[https://github.com/yourusername/monet-style-transfer-cyclegan](https://github.com/yourusername/monet-style-transfer-cyclegan)
