# Collab_filteration_python

# MovieLens Collaborative Filtering with SVD

This project implements a collaborative filtering model using **Singular Value Decomposition (SVD)** for the MovieLens dataset. The model uses 5-fold cross-validation to evaluate its performance and visualize predicted ratings versus actual ratings.

## Features
- **Collaborative Filtering**: Uses SVD for predicting user ratings for movies based on collaborative filtering.
- **Cross-Validation**: Implements 5-fold cross-validation to ensure robust model performance.
- **Visualization**: Plots scatter plots of real vs. predicted ratings for each fold, including the RMSE score for each fold.
- **RMSE Calculation**: Calculates and outputs RMSE for each fold, and the average RMSE across all folds.
- **CSV Export**: Saves RMSE scores to a CSV file (`rmse_scores_folds.csv`).

## Requirements
- Python 3.x
- numpy
- pandas
- scikit-learn
- matplotlib
- requests (for downloading dataset)

You can install the required libraries using:
```bash
pip install numpy pandas scikit-learn matplotlib requests
```

## How to Run
1. Clone the repository.
2. Run the script in your Python environment:
   ```bash
   python your_script.py
   ```
3. The script will:
   - Download and preprocess the MovieLens dataset.
   - Apply SVD with 5-fold cross-validation.
   - Save the RMSE results to a CSV file.
   - Generate scatter plots comparing predicted vs. real ratings.

## Future Plans
- Implement a Flask app for serving the model and visualizations via a web interface.

Enjoy exploring collaborative filtering with SVD!
