# Data Preprocessing Utilities

Reusable data preprocessing for ML pipelines.

## Features
- Missing value imputation
- Feature scaling (Standard, MinMax)
- Categorical encoding (OneHot, Label)
- Text tokenization

## Usage
```python
from preprocessing import Pipeline
pipe = Pipeline([Imputer(strategy='mean'), Scaler(method='standard')])
X_clean = pipe.fit_transform(X)
```

## License
MIT
