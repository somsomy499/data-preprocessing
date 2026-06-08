# Data Preprocessing Utilities

Reusable data preprocessing utilities for ML pipelines.

## Features
- Missing value imputation
- Feature scaling (Standard, MinMax)
- Categorical encoding (OneHot, Label)
- Text tokenization
- Image resizing and normalization

## Usage
```python
from preprocessing import Pipeline

pipe = Pipeline([
    Imputer(strategy='mean'),
    Scaler(method='standard'),
    Encoder(method='onehot')
])
X_clean = pipe.fit_transform(X)
```

## License
MIT
