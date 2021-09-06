# Image Denoising Datasets
## _Common benchmarks for image denoising_

✨Disclaimer✨ These datasets are just collected here for convenience, no ownership claimed and no guarantees provided.

The color versions are preceded by **C** in the folder name. Sorted by increasing size:

- Set5
- Set14
- BSD68
- Sun_Hays80
- Urban100
- Manga109


## _Real microscopy denoising dataset_

We collected dataset for real (fluorescence) widefield microscopy denoising, published in ECCV 2020 BioImage Computing (BIC) Workshop. It also contains data for super-resolution, with structured illumination ground-truth. It can thus be used for the joint image denoising and SR task.

It contains 144,000 images: **360 sets** each comprising **400 repeated captures** (4 times larger than the most recent prior work). Averaging 1, 2, 4, 8, or 16 captures gives images with varying noise levels, and the ground-truth is obtained by averaging the 400 captures.

That dataset can be found [-> here <-](https://github.com/IVRL/w2s).
