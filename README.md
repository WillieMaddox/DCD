# DCD
Detecting and counting things in images using deep learning.

# The goal of this project is to explore various ways of detecting and counting using the MNIST dataset.

1. Mosaics (n x n x 1):
  - Example 1: detection (multi-label classification) mosaic_size=(2 x 2) input_shape=(bs,56,56,1) -> output_shape=(bs,10)
  - Example 2: counting mosaic_size=(2 x 2) input_shape=(bs,56,56,1) -> output_shape=(bs,1)
2. Channel-wise stacking (1 x 1 x m):
  - Example 1: detection (multi-label classification) n_channels=5 input_shape=(bs,28,28,5) -> output_shape=(bs,5)
  - Example 2: counting n_channels=5 input_shape=(bs,28,28,5) -> output_shape=(bs,1)
