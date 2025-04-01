# Animal Faces Classification

## Project Description
This project utilizes machine learning to classify images of animal faces using Python and the PyTorch library. The model is trained on the "Animal Faces" dataset from Kaggle.


## Downloading Data

The dataset can be downloaded from Kaggle using the `opendatasets` library. To do this, run the following code:

```python
import opendatasets as od
od.download("https://www.kaggle.com/datasets/andrewmvd/animal-faces")
```

## Running the Project

1. Ensure you have downloaded the data and saved it in the appropriate directory.
2. Open `demo.ipynb` in Jupyter Notebook or Jupyter Lab.
3. Execute the cells sequentially to train and test the model.

## Device Configuration
The project detects available hardware acceleration and automatically adjusts computation:

```python
device = "mps" if torch.mps.is_available() else "cpu"
print("Device available: ", device)
```

## Results Visualization
The `matplotlib` library is used to visualize results. You can display sample images and track the training progress of the model.

## Author
This project was created for learning and exploring machine learning techniques in image classification by ‪@OmarMAtef‬



