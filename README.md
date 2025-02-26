# California Housing Analysis

## Description
This project analyzes the California Housing dataset using `scikit-learn` and `pandas`. It explores key features, performs exploratory data analysis (EDA), and prepares the data for potential machine learning applications.

## Features
- Importing the dataset using `scikit-learn`
- Creating a Pandas DataFrame for easy data manipulation
- Displaying and analyzing the first few rows of the dataset

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/California_Housing_Analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd California_Housing_Analysis
   ```
3. Install dependencies:
   ```bash
   pip install pandas scikit-learn
   ```

## Usage
Run the Python script to load and display the dataset:
```python
from sklearn.datasets import fetch_california_housing
import pandas as pd

data = fetch_california_housing()
df = pd.DataFrame(data.data, columns=data.feature_names)
print(df.head())
```

## Contributing
Feel free to fork this repository and submit pull requests to enhance the analysis.

## License
This project is open-source and available under the MIT License.

