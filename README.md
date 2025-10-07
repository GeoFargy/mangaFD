# Manga Face Detection

This repository contains the code used for the mangaFD YOLO12-S dataset.

## Project Structure

```
.
├── data/           # Contains dataset files, annotations, and YAML configs
├── experiments/    # Training, evaluation, and conversion scripts
├── models/         # Model architectures and pre-trained weights
├── utils/          # Utility functions and helper scripts
├── requirements.txt
├── README.md
```

- **data/**: Stores datasets, annotation files, and configuration YAMLs for dataset management.
- **experiments/**: Includes scripts for training, evaluating, and converting models.
- **models/**: Contains model definitions, architectures, and any pre-trained weights.
- **utils/**: Utility scripts and helper functions used throughout the project.


## Usage

1. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```
2. Run the desired training or conversion script, for example:
    ```sh
    python experiments/training_FD.py
    ```

## Datasets

The project supports MangaFD and Manga109 datasets, configurable via the provided YAML files. The expected structure should be of this way:

```
data
├── images
│   ├── train
│   ├── val
├── labels
│   ├── train
│   ├── val
```

