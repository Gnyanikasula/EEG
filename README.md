# Harmful Brain Activity Classification

## Project Description

This project utilizes the advanced MobileNetV3 Large architecture for multi-class classification across 6 distinct categories of spectrograms derived from EEG data. Techniques like MixUp and RandomCutout are employed for data augmentation.

## Models Used

- **MobileNetV3 Large**: Used for classification.
- **Differentiable KL Divergence Loss**: Employed as the loss function for training.

The validation loss of 1.0537 serves as the primary evaluation metric.

## Repository Contents

- `mobilenet.ipynb`: Jupyter Notebook containing the implementation details, data preprocessing, and model training process.

## Results

- Validation Loss: 1.0537

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/Gnyanikasula/EEG.git
   ```
2. Navigate to the project directory:
   ```sh
   cd EEG
   ```
3. Open the Jupyter Notebook to explore the code and results:
   - `mobilenet.ipynb`

## Future Work

- Further model fine-tuning.
- Exploring additional data augmentation techniques.
- Increasing the dataset size for better generalization.

## Contact

For any inquiries or contributions, please reach out via [GitHub Issues](https://github.com/Gnyanikasula/EEG/issues).
