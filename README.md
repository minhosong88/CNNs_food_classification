# CNN-Based Food Image Classification

#### Minho Song

## Overview

This project focuses on using Convolutional Neural Networks (CNNs) to classify food images from the Food-11 dataset. The project involves experimenting with different CNN architectures, evaluating their performance using F-1 scores, and applying transfer learning with ResNet50.

## Dataset

- **Source**: [Kaggle - Food-11 Image Dataset](https://www.kaggle.com/datasets/trolukovich/food11-image-dataset)
- **Description**: The dataset contains 16,643 food images categorized into 11 major food categories. For this project, a random extraction of 3,000 images was performed due to computational constraints.

## Project Structure

- `food_classification.ipynb`: Main Jupyter notebook containing the entire workflow, including data preprocessing, model building, and evaluation.
- `requirements.txt`: List of dependencies required to run the notebook.
- `.gitignore`: Excludes unnecessary files from the repository.

## Key Features

- **Evaluation Metric**: F-1 score was chosen as the evaluation metric to balance precision and recall, which is crucial for minimizing both false positives and false negatives in food categorization.
- **CNN Architectures**: Several CNN architectures were explored, including basic CNN models, ResNet-style models, and transfer learning with ResNet50.
- **Cross-Validation**: Nested cross-validation with stratified k-fold was used to ensure robust model evaluation.
- **Visualization**: Comprehensive visualizations of model performance, including training history and ROC curves.

## How to Use

1. **Clone the repository**:

```bash
   git clone https://github.com/minhosong88/convolution_neural_network.git
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Run the notebook**: Open `food_classification.ipynb` in Jupyter Notebook and execute the cells to reproduce the results.

## Results

The project found that simpler CNN architectures outperformed more complex models like ResNet in this specific task, indicating that model complexity does not always translate to better performance.

## References

- Moro, S., Rita, P., and Cortez, P. (2012). Bank Marketing. UCI Machine Learning Repository. [https://doi.org/10.24432/C5K306](https://doi.org/10.24432/C5K306)
- Kaggle - Food-11 Image Dataset. [https://www.kaggle.com/datasets/trolukovich/food11-image-dataset](https://www.kaggle.com/datasets/trolukovich/food11-image-dataset)
