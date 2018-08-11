# Horizon Segmentation

Using DeepLabv3 to segment areial images and then extract the horizons.

- Trained with xception65 feature extractor pre-trained on ImageNet.
- CRF postprocessing via DeepCRF

## Dependencies

Python 3.6

```shell
pip install tensorflow
pip install matplotlib
pip install pillow
pip install scipy
conda install -c conda-forge pydensecrf
```
