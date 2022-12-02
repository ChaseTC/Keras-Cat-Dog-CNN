# Cat Dog Classification with Keras CNN

A basic project using Microsoft's Cats and Dogs Dataset with the goal of learning Keras and CNNs.

## Data Prepartion
- Download the dataset: https://www.microsoft.com/en-us/download/details.aspx?id=54765
- Run the `data-prep` notebook to preprocess the data and store as a pickle file.

## Training the model
The model was trained and tuned using Google Colab in `KerasCatDogCNN.ipynb`

- The data was uploaded to Google Drive and mounted to Google Colab
- Hyperparameter tuning was done using Keras Tuner's Hyperband search
- Statistics were saved for TensorBoard