# Boolean transcription factor network for hierarchical differentiation of myeloid progenitor cells

## Abstract

+ language: python3 [>= 3.8](https://devguide.python.org/versions/)
+ library dependencies: ipywidgets, matplotlib, numpy, pandas, tellurium.
+ date: autumn 2023
+ author: Elmar Bucher
+ contact: https://github.com/elmbeech/grn_myeloid_progenitor/issues
+ doi: https://doi.org/10.5281/ZENODO.8176399
+ license: [GPL >= v3](https://www.gnu.org/licenses/gpl-3.0.en.html)
+ user manual: this README.md file
+ description:
  python3 tellurium implementation and analysis from
  [krumsiek et al.'s 2011 published](https://doi.org/10.1371/journal.pone.0022649)
  myeloid progenitor cells differentiation gene regulatory network.


## HowTo guide

### Run on google colab

1. in a web browser open:
   https://github.com/elmbeech/grn_myeloid_progenitor/blob/main/engr_e542_fall2023_sysbio_network_project_sim.ipynb
1. click the: `Open in Colab` link.
1. run the first code cell to install `libncurses5` C and `tellurium` python3 library.
1. once the first cell is run, it will crash with the message: `Your session crashed for an unknowenreason.`
1. no worries! all fine. now you can continue to run the other cells as usual.


### Run locally

1. it is assumed python3 and all library dependencies are installed and running.
1. clone the notebook locally: `git clone https://github.com/elmbeech/grn_myeloid_progenitor.git`
1. open the notebook: `jupyter lab engr_e542_fall2023_sysbio_network_project_sim.ipynb`
1. skip the first cell! `libncurses5` and `tellurium` should already be installed.
1. from the second code cells onwars, run the notebook as usual.

## Cite:
```bibtex
@Misc{bucher2023,
  author    = {Bucher, Elmar},
  title     = {elmbeech/grn_myeloid_progenitor: python3 tellurium myeloid progenitor cells differentiation gene regulatory network implementation and analysis.},
  year      = {2023},
  copyright = {Open Access},
  doi       = {},
  publisher = {Zenodo},
}
```
