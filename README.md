# **Protein Stability Prediction from Point Mutations**<a id="h.2kmp492q5ije"></a>

Predicting the change in Gibbs free energy (ΔG) caused by single-point amino-acid mutations helps evaluate protein stability and guide protein-engineering efforts.\
This repository contains:

| Path                          | Purpose                                                                                                                                     |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| `data/mutated.csv`            | Curated dataset of 2 099 wild-type and mutant protein sequences with experimentally measured ΔG values & Prediction Accuracy Plot           |
| `Delta_G_Prediction Notebook` | End-to-end Jupyter notebook that loads the dataset, builds TensorFlow and scikit-learn models, and benchmarks their ΔG prediction accuracy. |

**Quick Start**

\


\# Clone the repo

[elexipaul/ML-Training](https://github.com/elexipaul/ML-Training)

_Happy modeling & may your proteins stay stable!_

\
\
\



## **_Requirements_**<a id="h.jx5bns3nivlx"></a>

_The notebook was last tested with:_

|                |               |
| -------------- | ------------- |
| **_Package_**  | **_Version_** |
| _TensorFlow_   | _2.19.0_      |
| _scikit-learn_ | _1.7.0_       |
| _pandas_       | _2.2+_        |
| _seaborn_      | _0.13.2_      |
