# MISe

[![DOI](https://zenodo.org/badge/599198442.svg)](https://zenodo.org/badge/latestdoi/599198442)

This is the official repository of the software MISe - Multidimensional Image Segmentation. MISe offers a suite of image segmentation and analysis algorithms developed using the Image Foresting Transform (IFT) framework, coupled with image visualization and volume rendering tools. Living up to its name, MISe accepts the workload with various 2D, 3D, and 4D images.

## Installation Guide

This tutorial was tested on Ubuntu 22.04. Ensure you have libift compiled on your machine. The following packages are necessary to build the Qt user interfaces:

```console
apt install qt6-base-dev libqt6charts6-dev
```

Next, you are all set to compile MISe:

```console
cd PATH_FOR_MISE_SOURCE_CODE
qmake6 IFT_DIR="PATH_FOR_LIBIFT_DIR"
make
```

## Citation

If you find this software useful for your research, please cite it as follows.

```bibtex
@article{ilan2023mise,
  title={LIDS-UNICAMP: MISe: Multidimensional Image Segmentation},
  DOI={10.5281/zenodo.8280035},
  publisher={Zenodo},
  author={Ilan Francisco da Silva and Taylla Milena Theodoro},
  url = {https://github.com/LIDS-UNICAMP/MISe},
  year={2023},
  month={Aug}
}

@article{falcao2004image,
  title={The image foresting transform: Theory, algorithms, and applications},
  author={Falcao, Alexandre X and Stolfi, Jorge and de Alencar Lotufo, Roberto},
  journal={IEEE transactions on pattern analysis and machine intelligence},
  volume={26},
  number={1},
  pages={19--29},
  year={2004},
  publisher={IEEE}
}
```
