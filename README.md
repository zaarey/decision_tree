## Titanic Survival Prediction - Decision Tree Classifier

This project demonstrates the usage of a **Decision Tree Classifier** to predict passenger survival on the **Titanic** dataset. Using select features, the model aims to determine the likelihood of survival based on passenger characteristics.

### Project Overview

1. **Data Preprocessing**:
   - **Age Column**: Filled missing values using the median age, then applied `fillna()` to complete the column.
   - **Sex Column**: Converted categorical values (Male/Female) to numeric values using label encoding for easier processing by the model.

2. **Modeling**:
   - Utilized a Decision Tree Classifier to fit the dataset using features like `Pclass`, `Age`, `Fare`, and the encoded `Sex` values.
   - Predicted the **Survived** column (target variable) to evaluate model performance.

### Features Used for Prediction

- **Pclass**: Passenger class (1st, 2nd, or 3rd).
- **Age**: Passenger age (with NaN values replaced by the median).
- **Fare**: Ticket fare.
- **Sex**: Encoded numerically as `sex_n`.

### Libraries Used

```python
import pandas as pd
import math
from sklearn.tree import DecisionTreeClassifier
from sklearn.preprocessing import LabelEncoder
```
### Installations
```bash
pip install pandas sklearn
```
