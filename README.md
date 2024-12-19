# GlobalAIHub-ImageProcessing
## Overview
This project aims to classify animal species using a **Convolutional Neural Network (CNN)** while evaluating model performance under various lighting conditions. The robustness of the model is enhanced using **color constancy techniques**, which address challenges caused by different lighting environments.

---

## Objectives
- **Train a CNN model** to classify animal species accurately.
- Evaluate the model's performance on:
  - Original test set.
  - Test set with manipulated lighting conditions (e.g., purple light).
  - Test set preprocessed with color constancy techniques.
- Analyze and compare the results to identify areas of improvement.

---

## Dataset
The dataset contains images of various animal species, divided into **training** and **test** sets.  
Each image is processed to simulate different lighting conditions and corrected using color constancy methods to enhance the model's robustness.

---

## Methodology

### 1. Data Preprocessing
- Images were resized to a fixed size for consistent input to the CNN.
- Data augmentation techniques were applied to enhance diversity and improve generalization.

### 2. Model Architecture
- A CNN model was designed and trained from scratch to classify images into their respective species categories.

### 3. Lighting Manipulations
- Simulated lighting changes (e.g., **purple**, **green**, and **yellow** lights) to test the model's adaptability to varying conditions.
- Evaluated the model's classification accuracy under these altered lighting conditions.

### 4. Color Constancy Techniques
- Applied **Grey World color constancy** to mitigate the effects of lighting changes.
- Preprocessed the manipulated test set to enhance the model's robustness under varying lighting conditions.

### 5. Evaluation
- Compared **accuracy** and **loss** across different test sets to analyze the model's adaptability and performance under diverse scenarios.

---

## Results

| Test Set                          | Accuracy  |
|------------------------------------|-----------|
| **Original Test Set**             | 66.30%    |
| **Purple Manipulated Test Set**   | 18.30%    |
| **Color Constancy Test Set**      | 61.90%    |

### Key Insights
- **Original Test Set**: The model achieved moderate accuracy, reflecting its ability to classify animal species under standard conditions.  
- **Purple Manipulated Test Set**: Accuracy dropped significantly, highlighting the model's sensitivity to changes in lighting.  
- **Color Constancy Test Set**: Applying color constancy improved accuracy, demonstrating its effectiveness in mitigating lighting variations.  

## Links
- [Kaggle Notebook](https://www.kaggle.com/code/evvalzcanolu/globalaihub-imageprocessingbootcamp)
