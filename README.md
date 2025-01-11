# Dimensionality Reduction with K-Means and Gaussian Naive Bayes

## Overview
This project demonstrates the use of dimensionality reduction techniques and Gaussian Naive Bayes (GNB) classifier to optimize model performance. By reducing the number of features from 561 to 50 using a clustering-based approach (K-Means), the model achieves improved metrics and reduced training time without compromising accuracy.

## Features
- Original dataset with 561 features.
- Dimensionality reduction using K-Means clustering.
- Training a Gaussian Naive Bayes classifier.
- Comparison of model metrics before and after dimensionality reduction.

## Key Results
- **Improved Metrics:** Higher accuracy scores after reducing the feature set.
- **Reduced Training Time:** Faster model training with the reduced feature set.
- **Optimized Performance:** Maintains good accuracy with fewer features.

## Technologies Used
- **Python**: Programming language.
- **scikit-learn**: For Gaussian Naive Bayes implementation and K-Means clustering.
- **NumPy**: For numerical computations.
- **Matplotlib/Seaborn**: For visualizing results (if applicable).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/naveencreation/Dimensionality-Reduction-with-K-Means-and-Gaussian-Naive-Bayes..git
   ```
2. Navigate to the project directory:
   ```bash
   cd dimensionality-reduction-kmeans-gnb
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your dataset (ensure it matches the format expected by the script).
2. Run the script for training the model with 561 features:
   ```bash
   python train_original_features.py
   ```
3. Run the script for training the model with reduced features:
   ```bash
   python train_reduced_features.py
   ```
4. Compare the results and observe the metrics and training times.

## Files
- `train_original_features.py`: Script for training the model on 561 features.
- `train_reduced_features.py`: Script for training the model after dimensionality reduction.
- `requirements.txt`: List of required Python libraries.

## Results
- **Accuracy with 561 features:** [0.7314751869476547].
- **Accuracy with 50 features:** [0.7959738846572362].
- **Training time comparison:** [0.1424 seconds].

## Conclusion
This project highlights the effectiveness of dimensionality reduction in improving machine learning model efficiency. By reducing the feature set with K-Means, the Gaussian Naive Bayes classifier achieves better accuracy and significantly reduces training time.


## Contact
For any inquiries or feedback, please contact [naveenselvan0004@gmail.com].
