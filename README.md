# An investigation of p53 and DNA damage by William Cesaretti
### Indiana University Bloomington 
### 12/12/23

## Abstract 
(Thanks to Elmar Bucher for format)
+ Language: python3 [>= 3.8](https://devguide.python.org/versions/)
+ Library dependencies: ipywidgets, matplotlib, numpy, pandas, tellurium.
+ License: [GPL >= v3](https://www.gnu.org/licenses/gpl-3.0.en.html)
+ Date: December 2023
+ Author: William Cesaretti
+ Contact: wjcesaretti@gmail.com
+[![DOI](https://zenodo.org/badge/730505367.svg)](https://zenodo.org/doi/10.5281/zenodo.10371428)
+ User manual: this README.md file
+ Description: python3 tellurium implementation and analysis from
  [Zhang et al.'s 2007 published](https://pubmed.ncbi.nlm.nih.gov/17245126/) Exploring mechanisms of the DNA-damage response: p53 pulses and their possible relevance to apoptosis
+ This notebook is my semester work for the course [ENGR E542 Introduction to Computational Bioengineering](https://academics.iu.edu/courses/bloomington/engr-e-542-introduction-to-computational-bioengineering.html) by Prof. James Glazier.

## Run on Google Colab
1. In a web browser open:
   [https://github.com/wjcesaretti/p53Investigation/blob/main/finalProject1.ipynb](https://github.com/wjcesaretti/p53Investigation/blob/main/finalProject1.ipynb)
1. Click the: `Open in Colab` link.
1. Once you get to the first code cell, run it to install `libncurses5` C and `tellurium` python3 library.
1. Once the cell is run, it will crash with the message: `Your session crashed for an unknown reason.`
1. This is fine. Now just continue to run the other cells as usual.

## Run locally
1. It is assumed python3 and all library dependencies are installed and running.
1. Clone the notebook locally: `git clone https://github.com/wjcesaretti/p53Investigation.git`
1. Open the notebook: `jupyter lab finalproject1.ipynb`
1. Skip the installing packages cell! `libncurses5` and `tellurium` should already be installed.
1. From the second code cell onwards, run the notebook as usual.

## Cite
```bibtex
@Misc{cesaretti2023,
  author    = {Cesaretti, William},
  title     = {wjcesaretti/An investigation of p53 and DNA damage},
  year      = {2023},
  copyright = {Open Access},
  doi       = {10.5281/ZENODO.10371428},
  publisher = {Zenodo},
}
```
