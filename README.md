# Introduction to Affine Image Registration

Part of the 2019-ImageXD Image Registration tutorial

## Software required

- **Python**

  If you are new to Python, please install the
  [Anaconda distribution](https://www.continuum.io/downloads) for
  **Python version 3** (available on OSX, Linux, and Windows).
  Everyone else, feel free to use your favorite distribution, but
  please ensure the requirements below are met:

  - `python` >= 3.6
  - `numpy` >= 1.12
  - `scipy` >= 1.0
  - `matplotlib` >= 2.1
  - `scikit-image` >= 0.15


- **Jupyter**

  The lecture material includes Jupyter notebooks.  Please follow the
  [Jupyter installation instructions](http://jupyter.readthedocs.io/en/latest/install.html),
  and ensure you have version 4 or later:

  ```bash
  $ jupyter --version
  4.4.0
  ```

  Please also activate Jupyter Widgets:

  ```
  pip install -q ipywidgets
  jupyter nbextension enable --py --sys-prefix widgetsnbextension
  ```

## Download complete ImageXD 2019 image registration lecture material

Clone the repository at [https://github.com/KitwareMedical/2019-ImageXD-Registration-Tutorial](https://github.com/KitwareMedical/2019-ImageXD-Registration-Tutorial)


## Install into an environment

Optionally, create a new conda environment or virtual environment.

Then, install the packages:

  `$ pip3 install --upgrade --pre --upgrade-strategy eager -r requirements.txt`

