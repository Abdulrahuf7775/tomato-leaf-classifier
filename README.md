# Tomato Leaf Disease Classifier

A PyTorch CNN that classifies tomato leaf images into 10 disease classes.

- Dataset: https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf
- Input: 256x256 RGB images
- Model: custom CNN (`TomatoCNN`), weights in `best_model.pt`
- Best validation accuracy: FILL_IN
- Test accuracy: FILL_IN

## Usage
1. Download the dataset from Kaggle.
2. Open the notebook in Google Colab.
3. Load the weights:

```python
model = TomatoCNN(num_classes=10)
model.load_state_dict(torch.load("best_model.pt", map_location="cpu"))
model.eval()
```
