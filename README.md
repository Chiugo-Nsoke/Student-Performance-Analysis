# Student Performance Analysis Project

This repository contains an analysis of factors influencing student performance. The project uses Python libraries to explore, preprocess, and analyze data, applying machine learning techniques to predict performance outcomes.

## Features

- **Data Cleaning**: Handling missing values and outliers.
- **Exploratory Data Analysis (EDA)**: Visualizing trends in the dataset.
- **Feature Engineering**: Preparing data for machine learning.
- **Machine Learning**: Logistic Regression for prediction.

## Getting Started

### Prerequisites

To run this project, ensure you have Python 3.11+ installed. The required libraries are listed in the `requirements.txt` file.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Chiugo-Nsoke/Student-Performance-Analysis.git
   cd Student-Performance-Analysis
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Setting Up Ipywidgets

This project also uses **ipywidgets** for interactive widgets in Jupyter Notebook. To install and enable ipywidgets, run the following commands:

```bash
pip install ipywidgets
jupyter nbextension enable --py widgetsnbextension
jupyter nbextension install --py widgetsnbextension
```

### Usage

1. Place your dataset in the root directory of the project.
2. Open the Jupyter notebook `StdPerfProjectDS.ipynb`:
   ```bash
   jupyter notebook StdPerfProjectDS.ipynb
   ```
3. Run the cells to execute the analysis and see results.

### Dataset

The dataset contains information on various factors affecting student performance, including:

- Teacher Quality
- Parental Education Level
- Hours Studied
- Exam Scores

## Results

- Missing values were handled by dropping rows with significant gaps.
- Outliers in numerical features were capped using the capping method.
- A logistic regression model was trained, achieving high accuracy in predictions.

## Technologies Used

- Python
- Libraries: `numpy`, `pandas`, `seaborn`, `matplotlib`, `scipy`, `sklearn`, `ipywidgets`

## Contributing

Feel free to fork this repository and create pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

