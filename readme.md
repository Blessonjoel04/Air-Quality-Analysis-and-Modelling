# Air Quality Analysis and Modelling

This project focuses on predicting air quality using machine learning models. It includes extensive data exploration, preprocessing, and evaluation of various algorithms to identify the best-performing model.

## Project Overview

Air pollution is a significant global concern, and accurately predicting air quality is vital for public health and environmental monitoring. This project uses a dataset with multiple features related to air quality, categorizing the air quality index (AQI) into four categories:
- `Good`
- `Moderate`
- `Poor`
- `Hazardous`

### Models Used:
1. Support Vector Machine
2. Naive Bayes
3. Decision Tree
4. Extra Tree Classifier
5. Random Forest
6. Ada Boost Classifier
7. Gradient Boosting Classifier

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/Blessonjoel04/Air-Quality-Analysis-and-Modelling
pip install -r requirements.txt
```


## Results

| Model                  | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| Support Vector Machine | 94.40%   | 94.40%    | 94.40% | 94.40%   |
| Naive Bayes            | 92.16%   | 92.18%    | 92.16% | 92.22%   |
| Decision Tree          | 91.92%   | 91.92%    | 91.92% | 91.92%   |
| Extra Tree Classifier  | 91.28%   | 91.28%    | 91.28% | 91.28%   |
| Random Forest          | 95.44%   | 95.44%    | 95.44% | 95.44%   |
| AdaBoost Classifier    | 73.68%   | 73.68%    | 73.68% | 73.68%   |
| Gradient Boosting      | 95.28%   | 95.28%    | 95.28% | 95.28%   |