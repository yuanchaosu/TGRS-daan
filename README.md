demo of DAAN
# DAAN: A Deep Autoencoder-based Augmented Network for Multilinear Hyperspectral Unmixing

**Note:** DAAN codes are intended for academic communication only and may not be used commercially.

# This demo of DAAN was made by Zhiqing Zhu and Yuanchao Su in July 2023.
# Contact: Yuanchao Su (suych3@xust.edu.cn) and Lianru Gao (gaolr@aircas.ac.cn).
## Architectures and Systems
* DAAN can run under X86 architectures.
* The demo was tested under Windows 11.\
#---------------------------------------------------------------------------------------------\
├── Readme.md\
├── Environment: Python 3.8.10 and PyTorch  2.0.1 \
├── Demo\
│   └── DAAN.py\
├── Test data: real and synthetic data sets.\
│   ├──  data_real(Real data)\
│   │     ├──Y.npy(Moffett Field data)\
│   │     └──E.npy(Endmembers)\
│   └──  data_synthetic(Synthetic data)\
│         ├──Y.npy(Synthetic data)\
│         └──E.npy(Endmembers)\
└── Results files

## Specification
* 'demo_synthetic_data.py' uses synthetic hyperspectral data.
* 'demo_real_data.py' uses Moffett Field data.
