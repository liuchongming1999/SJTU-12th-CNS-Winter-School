# Tutorial II: Neuron software tutotial
---
1. **Simulation of point neuron**
    
2. **Simulation of neuron with dendtrites**

3. **Simulation of neuronal network**

4. **Simulation of real neuron from ModelDB**

---

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
# test the following code to see whether the environment is set well
from neuron import h
import numpy as np
import matplotlib.pyplot as plt
import plotly
import seaborn as sns
```

