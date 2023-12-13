# An Investigation of P53 and DNA damage 
## William Cesaretti
### Indiana University Bloomington 


## Details 
(Thanks to Elmar Bucher for format)
+ Language: python3 [>= 3.8](https://devguide.python.org/versions/)
+ Library dependencies: [tellurium](https://tellurium.readthedocs.io/en/latest/), [ipywidgets](https://ipywidgets.readthedocs.io/en/stable/),  [matplotlib](https://matplotlib.org/), [numpy](https://numpy.org/), [pandas](https://pandas.pydata.org/)
+ License: [GPL >= v3](https://www.gnu.org/licenses/gpl-3.0.en.html)
+ Date: December 2023
+ Author: William Cesaretti
+ Contact: wjcesaretti@gmail.com
+ [![DOI](https://zenodo.org/badge/730505367.svg)](https://zenodo.org/doi/10.5281/zenodo.10371428)
+ User manual: this README.md file
+ Description: python3 tellurium implementation and analysis from
  [Zhang et al.'s 2007 published](https://pubmed.ncbi.nlm.nih.gov/17245126/) Exploring mechanisms of the DNA-damage response: p53 pulses and their possible relevance to apoptosis
+ This repo constitutes my semester work for the course [ENGR E542 Introduction to Computational Bioengineering](https://academics.iu.edu/courses/bloomington/engr-e-542-introduction-to-computational-bioengineering.html) by Prof. James Glazier. 

## Contents
+ [Images](https://github.com/wjcesaretti/p53Investigation/tree/main/images) contains the images used in the notebook and other supporting materials
+ [Presentations and PDFs](https://github.com/wjcesaretti/p53Investigation/tree/main/presentationsAndPDFS) contains various slide decks and proposals from presentations during the semester
+ [Zhang related materials](https://github.com/wjcesaretti/p53Investigation/tree/main/zhangRelatedMaterials) hosts the paper the model is based on and the raw antimony string of the model; translated from SBML using [this](https://sys-bio.github.io/makesbml/) site

## Run on Google Colab
1. In a web browser open:
   [https://github.com/wjcesaretti/p53Investigation/blob/main/finalProject1.ipynb](https://github.com/wjcesaretti/p53Investigation/blob/main/finalProject1.ipynb)
1. Click the: `Open in Colab` link.
1. Once you get to the first code cell, run it to install `libncurses5` C and `tellurium` libraries.
1. This will produce the message: `Your session crashed for an unknown reason.`
1. Disregard the message and run the other cells as usual.

## Run locally
1. It is assumed that python and all library dependencies are installed and running.
1. Clone the notebook locally: `git clone https://github.com/wjcesaretti/p53Investigation.git`
1. Open the notebook: `jupyter lab finalproject1.ipynb`
1. Skip the installing packages cell! `libncurses5` and `tellurium` should already be installed.
1. Run the notebook as usual from the second code cell onwards.

## Cite
```bibtex
@Misc{cesaretti2023,
  author    = {Cesaretti, William},
  title     = {An Investigation of p53 and DNA damage},
  year      = {2023},
  doi       = {10.5281/ZENODO.10371428},
  publisher = {Zenodo},
  note = {Open Access}
}
```
