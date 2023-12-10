# Boolean transcription factor network for hierarchical differentiation of myeloid progenitor cells

## Abstract
+ Language: python3 [>= 3.8](https://devguide.python.org/versions/)
+ Library dependencies: ipywidgets, matplotlib, numpy, pandas, tellurium.
+ Date: autumn 2023
+ Author: Elmar Bucher
+ Contact: https://github.com/elmbeech/grn_myeloid_progenitor/issues
+ Doi: [![DOI](https://zenodo.org/badge/728492800.svg)](https://zenodo.org/doi/10.5281/zenodo.10343911)
+ License: [GPL >= v3](https://www.gnu.org/licenses/gpl-3.0.en.html)
+ User manual: this README.md file
+ Description:
  python3 tellurium implementation and analysis from
  [krumsiek et al.'s 2011 published](https://doi.org/10.1371/journal.pone.0022649)
  myeloid progenitor cells differentiation gene regulatory network.
+ This notebook is my semester work for class [ENGR E542 Introduction to Computational Bioengineering](https://academics.iu.edu/courses/bloomington/engr-e-542-introduction-to-computational-bioengineering.html) by Prof. James Glazier.

## Run on google colab
1. In a web browser open:
   https://github.com/elmbeech/grn_myeloid_progenitor/blob/main/engr_e542_fall2023_sysbio_network_project_sim.ipynb
1. Click the: `Open in Colab` link.
1. Run the first code cell to install `libncurses5` C and `tellurium` python3 library.
1. Once the first cell is run, it will crash with the message: `Your session crashed for an unknowenreason.`
1. No worries! All fine. Now you can continue to run the other cells as usual.

## Run locally
1. It is assumed python3 and all library dependencies are installed and running.
1. Clone the notebook locally: `git clone https://github.com/elmbeech/grn_myeloid_progenitor.git`
1. Open the notebook: `jupyter lab engr_e542_fall2023_sysbio_network_project_sim.ipynb`
1. Skip the first cell! `libncurses5` and `tellurium` should already be installed.
1. From the second code cells onwars, run the notebook as usual.

## Cite
```bibtex
@Misc{bucher2023,
  author    = {Bucher, Elmar},
  title     = {elmbeech/grn_myeloid_progenitor: python3 tellurium myeloid progenitor cells differentiation gene regulatory network implementation and analysis.},
  year      = {2023},
  copyright = {Open Access},
  doi       = {10.5281/ZENODO.10343911},
  publisher = {Zenodo},
}
```
