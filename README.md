# Climate Prediction Experiments

Short description: Predict surface air temperature (tas) and precipitation (pr) over a latitude-longitude grid from climate forcings (e.g., CO2, CH4, SO2, BC, Solar Radiation) using various deep learning architectures.

## Files

- `starter.ipynb`: Baseline CNN/ResNet pipeline.
- `fno.ipynb`: Fourier Neural Operator implementation and experiments (including split vs. combined outputs, input ablations).
- `vit.ipynb`: CNN+Vision Transformer hybrid with geographic and temporal embeddings.
- `3DConv.ipynb`: Exploratory 3D convolution model for spatio-temporal context.
- `toroidal.ipynb`: Experiment with toroidal (wrap-around) convolutions to respect global spatial boundaries.

## Usage

1. Open the notebooks in Jupyter.
2. Ensure your data (inputs/targets) paths are set correctly in each notebook.
3. Install required dependencies (e.g., PyTorch, numpy) in your Python environment.
4. Run cells to train/evaluate each model.

Feel free to adapt hyperparameters or data-loading code as needed. 
