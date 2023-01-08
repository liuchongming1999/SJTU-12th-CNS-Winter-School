# Tutorial I: Brain Inspired Computation
---
1. **Brain Inspired Computation - Based Part**
    1. MP model
    2. Hebbian leaning
    3. Hopfield model
    4. Building up a simple artifitial neural network
1. **Brain Inspired Computation - Advanced Part**
    1. Convolution and LeNet-5
    2. AlexNet and visual system

---

## Install dependencies


```bash
# new python environment for pytorch
conda create -n pytorch_for_winter_school python=3.9
# activate the new environment
conda activate pytorch_for_winter_school
# install basic packages for scientific computing
conda install -y numpy matplotlib scipy scikit-learn jupyter ipython pandas
# install pytorch for constructing artificial neural networks
conda install pytorch torchvision torchaudio -c pytorch -c nvidia -y
# open a local jupyter notebook
jupyter notebook
```
If you failed to install pytorch, then try to follow the construction from [here](https://pytorch.org/get-started/locally/).
