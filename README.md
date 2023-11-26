# Artistic Style Transfer

This assignment implements a novel Neural Style transfer algorithm, built on the top of pretrained VGG19 model (for image feature extraction)

## Dependencies

Make sure you have the following dependencies installed:

- Python `3.x`
- Jupyter Notebook
- TensorFlow `>=2.7`
- Pillow (PIL)
- NumPy
- Matplotlib

You can install these dependencies using the following command:

```
pip install jupyter tensorflow pillow numpy matplotlib
```

## Customization

- Create two folders in the same directory where the notebook is present:
  - "`/images`": for storing input images. Put your "`content.jpg`" and "`style.jpg`" under this directory.
  - "`/outputs`": for storing generated images.

## Results

The stylized images will be saved in the outputs directory during the training process. Feel free to explore different epochs and observe how the stylization evolves.
