
# Reconstructing Images from Brain Activity

This repository contains code and resources for reconstructing images from brain activity data using deep learning techniques.
## Overview

The notebook demonstrates the process of reconstructing images from fMRI data. It includes data preprocessing, model training, and image reconstruction steps.

## Data
- **Original data of brain activity and assossiated images**: [algonauts_2023_tutorial_data](https://drive.google.com/drive/folders/1DUf3nGNNFk6YjRjQtZPfAY5N105GoGJb?usp=drive_link)

The necessary datasets for this project can be downloaded from the following links:

- **Images Dataset**: [subj03_images.npy](https://drive.google.com/file/d/1wNh_EstCoNMQhRXbkbnCvy-SWMSBmFzW/view?usp=sharing)
- **Decoder File**: [fmri_decoder_subj03rhV3.pth](https://drive.google.com/file/d/1id9tqPkeRS298SdqWuBgqxcwZWeix0Hc/view?usp=sharing)

Please ensure to place these files in the appropriate directories as required by the notebook.

## Libraries and Dependencies

This project utilizes the following libraries:

- `torch`
- `torchvision`
- `numpy`
- `scikit-image`

Make sure to install these dependencies before running the notebook. You can install them using `pip`:

```bash
pip install torch torchvision numpy scikit-image
```

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/brain-decoder.git
    cd brain-decoder
    ```

2. **Download the datasets**:
    Place the downloaded datasets (`subj03_images.npy` and `fmri_decoder_subj03rhV3.pth`) in the project directory.

3. **Run the notebook**:
    Open and run the Jupyter Notebook `BrainDecoder_Subj03-RH.ipynb` to reproduce the results.

## Results
The notebook includes steps for evaluating the reconstructed images against the original ones. The evaluation metrics include Structural Similarity Index (SSIM).
![img1](https://github.com/user-attachments/assets/32d4113b-8b84-4219-8195-ec8cc7b57d3c)

![img2](https://github.com/user-attachments/assets/0b78310a-a255-40c7-9810-872727506205)
![img3](https://github.com/user-attachments/assets/9dc8d9f0-6223-4872-a3d0-1ade15d1feca)
