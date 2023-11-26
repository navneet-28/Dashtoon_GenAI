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

- There are two folders in the same directory where the notebook is present:
  - `"/images"`: for storing input images. Put your "`content.jpg`" and "`style.jpg`" under this directory. Sample content and style images are already present there.
  - `"/outputs"`: for storing generated style transfer images.

## Open the jupyter notebook

```
jupyter notebook
```

- Navigate to the `Dashtoon_GenAI_Navneet_Singh_200625.ipynb` file and open it.
- Run the notebook cell by cell or all cells together.

## Results

The stylized images will be saved in the outputs directory during the training process. Feel free to explore different epochs and observe how the stylization evolves.

### Citation

```
@misc{gatys2015neural,
      title={A Neural Algorithm of Artistic Style},
      author={Leon A. Gatys and Alexander S. Ecker and Matthias Bethge},
      year={2015},
      eprint={1508.06576},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
