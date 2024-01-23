# Machine Learning Project for Fruit Classification

This repository contains code for classifying fruits based on their physical characteristics, such as mass, width, height, and color score. The dataset used is "fruit_data_with_colors.txt" from Kaggle. 

## Key Steps:

1. **Data Exploration and Preprocessing:**
   - Import libraries (pandas, numpy, seaborn)
   - Load the dataset
   - Check for missing values and data types
   - Visualize distributions and relationships between features
   - Drop unnecessary text columns
   - Apply scaling to numerical features using MinMaxScaler

2. **Model Building and Evaluation:**
   - Split data into training and testing sets
   - Train a K-Nearest Neighbors (KNN) classifier
   - Evaluate model performance on the testing set
   - Demonstrate the impact of scaling on model accuracy
   - Tune the hyperparameter 'k' to find the optimal number of neighbors

## Results:

- The accuracy of the KNN model significantly improved from 53.33% to 93.33% after applying scaling.
- The best value of 'k' for this dataset was found to be around 8, achieving an accuracy of approximately 96%.

## Repository Structure:

- `README.md` (this file)
- `fruit_data_with_colors.txt` (dataset)
- `fruit_classification.ipynb` (Jupyter Notebook containing the code)

## To run the code:

1. Download or clone this repository.
2. Ensure you have Python and the required libraries installed (pandas, numpy, seaborn, sklearn).
3. Open the `fruit_classification.ipynb` notebook in Jupyter Notebook or a similar environment.
4. Execute the cells in the notebook sequentially.

## Further Exploration:

- Experiment with different classification algorithms (e.g., Random Forest, Support Vector Machines).
- Explore feature engineering techniques to potentially improve model performance.
- Investigate the impact of different scaling methods.
