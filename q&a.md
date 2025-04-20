### Question: 

### 1. Why are we converting images into numpy array before training?
#### a. Machine Learning Models Work with Numbers
Images are essentially grids of pixel values. Each pixel has:
- For grayscale: a single number (0–255)
- For color: three numbers (RGB channels)

So we convert images into NumPy arrays to represent these pixel values numerically in a format models can understand.

#### b. NumPy is Fast & Efficient Matrix Math
ML frameworks (like TensorFlow, PyTorch, or even OpenCV itself) are optimized for working with arrays and matrices.
NumPy arrays make it easy to do things like:
- Normalize pixel values (e.g., divide by 255)
- Resize, crop, or transform images
- Batch multiple images into one big array

#### c. Compatibility with ML Libraries
ML models expect inputs as tensors (multi-dimensional arrays). NumPy arrays:
NumPy arrays make it easy to do things like:
- Can be directly used or easily converted into tensors.
- Are the go-to data format for preprocessing and feeding data into models.


