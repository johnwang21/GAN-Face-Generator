## link for dataset:

https://www.kaggle.com/datasets/jessicali9530/celeba-dataset

## Requirement and Version

Highly suggest using device that has at least 8GB of GPU memory or more or use google colab Pro/+ for training

## How to run
1. upload homebrew_gans_final.ipynb to google colab
2. upload kaggle api key.json into file directory (step 1 of https://medium.com/unpackai/how-to-use-kaggle-datasets-in-google-colab-f9b2e4b5767c)
3. click run all


### Notes
- completed images will be in 'results' folder
- should take 3-6 hours to run depending on GPU
- you can save models for generator, discriminator and GAN as .h5 but you only need generator.h5 to produce images
- code can generate with saved generator.h5
