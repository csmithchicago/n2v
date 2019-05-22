# Noise2Void - Learning Denoising from Single Noisy Images

### Source
This code has been forked from [n2v](https://github.com/juglab/n2v) and is based on the work and paper "Noise2Void - Learning Denoising from Single Noisy Images" by Alexander Krull, Tim-Oliver Buchholz, and Florian Jug.

Paper: https://arxiv.org/abs/1811.10980

## Installation
This implementation will require the new [Tensorflow 2.0](https://www.tensorflow.org/install/) and access to a gpu.

It is recommended that this code be run in a virtual environment to help with package clutter. 
```
$ python -m venv project-name
$ cd project name
$ source bin/activate
(project-name) $
```
Clone the repository and cd into it.
```
(project-name) $ git clone https://github.com/csmithchicago/n2v.git
(project-name) $ cd n2v
```
Install the dependencies in the virtual environmment with pip:
```
(project-name) $ pip install -r requirements.txt
(project-name) $ pip install -e .
```
You are now ready to run Noise2Void.

## Example Notebooks
Jupyter notebook:
* [2D example simulated fluorescence](https://github.com/csmithchicago/n2v/blob/light-sheet/examples/2D/N2V_denoising2D.ipynb)
* [2D example SEM data](https://github.com/csmithchicago/n2v/blob/light-sheet/examples/2D/N2V_denoising2D-SEM.ipynb)
* [3D example](https://github.com/juglab/n2v/blob/master/light-sheet/3D/N2V_denoising3D.ipynb)
