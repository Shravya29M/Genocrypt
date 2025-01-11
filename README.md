
# GenoCryptNet: The Future of Secure Communication through DNA

## Overview
This repository contains the code and data for the research paper **"GenoCryptNet: The Future of Secure Communication through DNA"**. The paper introduces an innovative algorithm leveraging DNA steganography and cryptography for secure data transmission. The algorithm uses the least significant bits of DNA codons and combines them with encryption techniques to hide data, ensuring robust security and efficiency.

## Repository Structure
- **`ASCII_2.csv`**: The dataset mapping codons and DNA sequences to their ASCII values.
- **`Evaluation.py`**: Python script to evaluate the performance of the GenoCryptNet algorithm.
- **`README.md`**: This documentation file.
- **`code.ipynb`**: Jupyter notebook with step-by-step implementation and visualization of the algorithm.

## Features
- **Encryption Algorithm**: Implements a substitution cipher for initial encryption of plaintext.
- **DNA Encoding**: Converts encrypted text into DNA sequences using a predefined mapping.
- **Steganography**: Embeds the encoded DNA into an image using least significant bit (LSB) techniques.
- **Decryption and Decoding**: Extracts the hidden data from the image and decodes it back to plaintext.

## Usage
### Prerequisites
- Python 3.8 or later
- Required libraries: `numpy`, `pandas`, `opencv-python`, `matplotlib`


### Data
The **`ASCII_2.csv`** file contains the DNA codon mappings necessary for encoding and decoding operations.

## Results
- **Metrics Evaluated**: MSE, PSNR, SSIM, payload capacity.
- The GenoCryptNet algorithm exhibits minimal perceptual differences in images post-embedding and ensures high fidelity for hidden data.

