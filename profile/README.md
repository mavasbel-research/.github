# Hysteresis & Control Research

Research software by [Marco Vásquez Beltrán](https://github.com/mavasbel) on modelling and control of hysteresis, adaptive optics, and model-order reduction.

[![Thesis DOI](https://img.shields.io/badge/Thesis%20DOI-10.33612%2Fdiss.215199709-0055A5?style=flat-square)](https://doi.org/10.33612/diss.215199709)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0001--6199--9813-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0001-6199-9813)
[![MATLAB](https://img.shields.io/badge/MATLAB-Simulink-0076A8?style=flat-square)](https://www.mathworks.com/)
[![Python](https://img.shields.io/badge/Python-Jupyter-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)

> **PhD thesis:** [*Multi-loop Hysteresis and Recursive Remnant Control*](https://doi.org/10.33612/diss.215199709), University of Groningen, 2022.

---

### 🧲 Hysteresis modelling and remnant control

| Repository | Contents | Language |
|:---|:---|:---|
| [**matlab-preisach-model**](https://github.com/mavasbel-research/matlab-preisach-model) | Preisach operator classes, model fitting, Simulink models, remnant ILC experiments and measurements, with folders for the CDC 2019, CDC 2020 and TAC 2020 work | MATLAB, Simulink |
| [**matlab_duhem_model**](https://github.com/mavasbel-research/matlab_duhem_model) | Duhem and asymmetric Miller model ODEs, butterfly-loop fitting, Simulink models, and a remnant control experiment | MATLAB, Simulink |

### 🔭 Adaptive optics and experimental setups

| Repository | Contents | Language |
|:---|:---|:---|
| [**deformable_mirror**](https://github.com/mavasbel-research/deformable_mirror) | Simulation of a hysteretic deformable mirror: influence matrices, electrode layouts, Preisach actuators, control, and Zernike wavefront reconstruction | MATLAB |
| [**piezo_setup**](https://github.com/mavasbel-research/piezo_setup) | Lab setup code: Arduino SPI DAC driver, interferometer acquisition examples, and Python/MATLAB integration | Python, C++, C#, C, MATLAB |
| [**shack-hartmaan_sensor_integration**](https://github.com/mavasbel-research/shack-hartmaan_sensor_integration) | Shack–Hartmann sensor reading and DAQ test scripts | MATLAB |

### 📉 Model reduction and learning

| Repository | Contents | Language |
|:---|:---|:---|
| [**model_reduction**](https://github.com/mavasbel-research/model_reduction) | Model-order reduction studies for beam and PD-controlled models, with error bounds and ODE simulation comparisons | Python, Jupyter |
| [**openai-reinforcement-learning**](https://github.com/mavasbel-research/openai-reinforcement-learning) | Q-learning agent for the OpenAI Gym Lunar Lander environment | Python, PyTorch |
| [**tensorflow_hysteresis_models**](https://github.com/mavasbel-research/tensorflow_hysteresis_models) | TensorFlow/Keras starter: a subclassed CNN and a custom training loop, trained on MNIST | Python, TensorFlow |

---

### 📄 Publications

| Year | Title | Venue |
|:---:|:---|:---|
| 2023 | [Modeling and Analysis of Duhem Hysteresis Operators With Butterfly Loops](https://doi.org/10.1109/TAC.2023.3238177) | IEEE Transactions on Automatic Control |
| 2022 | [On the Characterization of Butterfly and Multiloop Hysteresis Behavior](https://doi.org/10.1109/TAC.2021.3109533) | IEEE Transactions on Automatic Control |
| 2021 | [Recursive Algorithm for the Control of Output Remnant of Preisach Hysteresis Operator](https://doi.org/10.1109/LCSYS.2020.3009423) | IEEE Control Systems Letters |
| 2020 | [Influence functions for a hysteretic deformable mirror with a high-density 2D array of actuators](https://doi.org/10.1364/AO.397472) | Applied Optics |
| 2020 | [Asymptotic Stability Analysis of Lur'e Systems With Butterfly Hysteresis Nonlinearities](https://doi.org/10.1109/LCSYS.2019.2921850) | IEEE Control Systems Letters |

The full record is on [ORCID](https://orcid.org/0000-0001-6199-9813).
