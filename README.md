# GAN-Image-Style-Transfer
**Unpaired Image-to-Image Translation for Monet-style Painting Generation**

## 📌 Overview
This project explores artistic style transfer by transforming real-world images into Monet-style paintings and vice versa. Since paired datasets are unavailable, a CycleGAN architecture has been implemented. This architecture leverages cycle consistency loss to ensure structural integrity while adopting artistic styles.

## Features
* Unpaired Image-to-Image Translation using CycleGAN.
* Monet-style Artistic Transfer from real photos.
* Bidirectional Translation – Monet -> Photo and Photo -> Monet.
* Multiple Model Versions (V1–V7) with architectural and training variations.
* Evaluation Metrics: FID and MiFID for generative quality & memorization bias.
*  Optimizations: Mixed Precision Training, Gradient Penalty, Perceptual Loss (VGG16).

## Tech Stack
* Frameworks: PyTorch, PyTorch Lightning.
* GAN Model: CycleGAN (Generators + Discriminators with cycle consistency loss).
* Image Processing: Torchvision, Pillow, NumPy.
* Evaluation: Fréchet Inception Distance (FID), Memorization-informed FID (MiFID).
* Optimizations: AMP (mixed precision), gradient clipping, spectral normalization.

## Project Structure
```text
GAN-Image-Style-Tranfer/
├── Trial models                 # The complete set of trial models
├── Final Model                  # The final CycleGAN model
├── README.md                    # Project documentation
└── LICENSE                      # License file
```

## License
**This project is for academic use only.**
