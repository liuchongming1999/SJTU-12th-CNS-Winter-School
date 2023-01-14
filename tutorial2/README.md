# Tutorial II: Neuron software tutotial
---
1. **Simulation of point neuron**
    
2. **Simulation of neuron with dendtrites**

3. **Simulation of neuronal network**

4. **Simulation of real neuron from ModelDB**

---
The 4 sections in the tutorial2 is the latest version. If you have any question about the tutorial or the NEURON software, please contact me at majingyang0119@sjtu.edu.cn.

--

## Install dependencies


```bash
# new python environment for pytorch
conda create -n neuron_for_winter_school python=3.9
# activate the new environment
conda activate neuron_for_winter_school
# install basic packages for scientific computing
conda install -y numpy matplotlib plotly seaborn ipykernel
# install neuron package for python
pip3 install neuron
Note that pip install method is only valid for MacOS and Linux, Windows users should refer to https://neuron.yale.edu/ftp/neuron/2019umn/neuron-quickstart.pdf
# test the following code to see whether the environment is set well
from neuron import h
import numpy as np
import matplotlib.pyplot as plt
import plotly
import seaborn as sns
```

