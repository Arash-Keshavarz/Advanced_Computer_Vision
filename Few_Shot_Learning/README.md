# Few-Shot Learning on Oxford 102 Flower Dataset

This project implements few-shot learning on the Oxford 102 Flower Dataset using contrastive loss and ResNet50 as a feature extractor.

## Setup

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook:
```bash
jupyter notebook
```

## Project Structure

- `few_shot_learning_flowers.ipynb`: Main notebook containing the implementation
- `requirements.txt`: List of Python dependencies
- `README.md`: This file

## Implementation Details

- **Architecture**: ResNet50 as feature extractor with trainable dense layers
- **Few-Shot Setup**: 3-way, 3-shot learning
- **Query Set**: 4 samples per class
- **Loss Function**: Contrastive Loss
- **Dataset**: Oxford 102 Flower Dataset (automatically downloaded via tensorflow-datasets)

## Features

1. ResNet50 feature extraction with fine-tunable dense layers
2. Contrastive loss implementation
3. Support set and query set generation
4. Prototype computation for few-shot learning
5. Episode-based training
6. Performance visualization

## Usage

Open the `few_shot_learning_flowers.ipynb` notebook and run the cells sequentially. The notebook includes:
1. Data loading and preprocessing
2. Model creation and setup
3. Few-shot learning implementation
4. Training loop
5. Results visualization
