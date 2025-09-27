# Cats vs Dogs CNN Classifier

This project is part of the **FreeCodeCamp Machine Learning with Python** course.

## Dataset
- Source: [FreeCodeCamp Cats and Dogs Dataset](https://cdn.freecodecamp.org/project-data/cats-and-dogs/cats_and_dogs.zip)
- Contains images of cats and dogs for training, validation, and testing.

## Model
- Convolutional Neural Network (CNN) with:
  - 3 Conv2D layers
  - MaxPooling
  - Dense layer with 512 neurons
  - Dropout for regularization
- Optimizer: Adam
- Loss: Binary Crossentropy

## Achievements
- Training Accuracy: 74%
- Validation Accuracy: 69%

## How to Run
1. Open `cats_vs_dogs_cnn.ipynb` in [Google Colab](https://colab.research.google.com/)  
2. Download the dataset from the link above and place it in the project folder structure:  
3. Run all cells sequentially.  

## Notes
- Uses `ImageDataGenerator` for data augmentation.  
- Final predictions visualized with probability labels.  

