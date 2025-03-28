# Models Folder

This folder contains all the machine learning models used in the project.

## Contents

- **Trained Models**: Saved trained models in various formats.
- **Model Metadata**: Information about the models, including training parameters and performance metrics.

## Trained Models

- `model_v1.pkl`: First version of the trained model.
- `model_v2.pkl`: Second version of the trained model.
- `model_v3.h5`: Third version of the trained model in HDF5 format.

## Model Metadata

- `model_v1_metadata.json`: Metadata for the first version of the model.
- `model_v2_metadata.json`: Metadata for the second version of the model.
- `model_v3_metadata.json`: Metadata for the third version of the model.

## Usage

1. Load the desired model using the appropriate library (e.g., `pickle` for `.pkl` files, `h5py` for `.h5` files).
2. Refer to the corresponding metadata file for information on the model's training parameters and performance metrics.

## Example

```python
import pickle

# Load model_v1
with open('model_v1.pkl', 'rb') as file:
    model_v1 = pickle.load(file)

# Use the model for predictions
predictions = model_v1.predict(data)
```
