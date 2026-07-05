# realmixgan
RealMixGAN: Accelerating GAN Convergence by Leaking Real Data Distribution into the Latent Space
This repository contains the implementation and visualizations for the RealMixGAN project performed during my IEEE CIS Kolkata Chapter Summer Internship 2025. The project explores a generator-input mixing strategy where noisy projections of real images are leaked into the generator latent space to accelerate convergence and improve mode coverage on MNIST.
Included:
- Reproducible PyTorch implementation of Standard GAN and RealMixGAN.
- Training scripts that produce loss curves, Wasserstein distance metrics, and sample images.
- Visualizations and final figures in `outputs/` and `docs/figures/`.
- Internship report (PDF) in `docs/`

## Features

- Improved GAN convergence
- Reduced Wasserstein Distance
- Stable adversarial training
- Dropout regularization
- MNIST implementation

## Project Structure

docs/
notebooks/
outputs/
src/
## Requirements

Python
PyTorch
NumPy
Matplotlib
## Installation

Install with:
pip install -r requirements.txt
## Usage

Open `notebooks/RealMixGAN.ipynb` for an interactive walkthrough or run the training script:
python src/train.py
This script trains both Standard GAN and RealMixGAN for the preset number of epochs and the outputs are saved to `outputs/` and sample figures to `docs/figures/`.
## Repository layout

`src/` contains dataset loader, model definitions, trainer, and visualization helpers. `notebooks/` contains the interactive notebook. `docs/` contains the internship report and final figures.
## Results

Final figures and generated images are saved to `outputs/` and `docs/figures/`.
-> 52.8% reduction in Wasserstein Distance
-> 22.1% reduction in Generator Loss
## License

This project is released under the MIT License.
## Authors

Ankit Sen,
Arghya Daw, 
Subhadip Malakar,
Sayan Biswas

Mentor: Dr. Sumanta Ray

IEEE CIS Kolkata Chapter — Summer Internship 2025

## Acknowledgement

This repository contains my copy of the project developed during the IEEE CIS Kolkata Chapter Summer Internship 2025.

The work was carried out collaboratively by the internship team under the mentorship of Dr. Sumanta Ray.
