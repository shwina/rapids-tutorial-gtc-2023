# Introduction to RAPIDS cuDF and cuML - GTC 2023

This repository contains the code for the NVIDIA GTC 2023 [Introduction to RAPIDS](https://www.nvidia.com/gtc/session-catalog/#/session/1666311693102001I3Qd) talk.

`NYCTaxi.ipynb` contains the code from the talk, and shows how to use the [cuDF](https://docs.rapids.ai/api/cudf/stable/) and [cuML](https://docs.rapids.ai/api/cuml/stable/) libraries in a GPU-accelerated data science pipeline.

`NYCTaxi-Blank.ipynb` is the same, but contains a few `#TODO` sections as exercises.

## Install RAPIDS and other dependencies

To run the notebooks in this repository, you'll need to install cuDF and cuML along with a few other dependencies.

Below, we show how to use `pip` to install `cudf` and `cuml`. Other installation options can be found [here](https://docs.rapids.ai/install).

```
pip install cudf-cu11 cuml-cu11 --extra-index-url=https://pypi.nvidia.com
```

### Other dependencies

```
pip install requests seaborn scikit-learn tqdm
pip install hvplot
```

## Try RAPIDS on Google Colab

Don't have access to a GPU, but still want to give RAPIDS a try? You can also run the [NYCTaxi notebook on Google Colab](https://colab.research.google.com/drive/1HMcxNFOudm7CbbOmQY5lDdYb0YD7Tj0z).
