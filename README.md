
# Deep Learning Training Notebooks

This repository contains a collection of Jupyter Notebooks focused on improving deep learning models through various techniques. Each notebook addresses specific aspects of training, optimization, and model architecture. Below is a description of each notebook included.

## Notebooks Overview

1. **[Solution]_0_OriginalModel.ipynb**
   - Implements the original baseline model as a reference point for later enhancements.

2. **[Solution]_1a_WeightIncreasing.ipynb**
   - Investigates the effects of increasing weights during training.
   - Suggests stabilization methods for better performance.

3. **[Solution]_1b_WeightIncreasing.ipynb**
   - Continues exploring weight initialization strategies to address training issues.

4. **[Solution]_2_BetterActivationFunction.ipynb**
   - Introduces improved activation functions such as ReLU, Leaky ReLU, and more.
   - Examines their influence on the convergence of the model.

5. **[Solution]_3_BetterOptimizer.ipynb**
   - Tests advanced optimization algorithms (e.g., Adam, RMSprop).
   - Compares their efficiency and effectiveness in improving training.

6. **[Solution]_4a_NormalizationInsideNetwork.ipynb**
   - Adds normalization techniques like Batch Normalization.
   - Explains their role in stabilizing and accelerating training.

7. **[Solution]_4b_NormalizationInsideNetwork.ipynb**
   - Further explores normalization approaches to improve model performance.

8. **[Solution]_5_SkipConnection.ipynb**
   - Introduces skip connections (ResNet-style).
   - Resolves vanishing gradient problems in deep networks.

9. **[Solution]_6_TrainLayerSeparately.ipynb**
   - Explores the benefits of training model layers separately.
   - Highlights strategies for optimizing deep networks.

10. **[Solution]_7_PreTrain&Finetune.ipynb**
    - Implements pre-training and fine-tuning.
    - Demonstrates transfer learning for specific use cases.

## How to Use

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project folder:
   ```bash
   cd <repository-folder>
   ```
3. Open the notebooks using Jupyter:
   ```bash
   jupyter notebook
   ```

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Machine learning libraries (PyTorch)
- Other dependencies specified in the notebooks.