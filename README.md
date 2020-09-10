# Tutorials for quantitative modeling
This repository provides tutorials for quantitative modeling using a variety approaches. In addition to the tutorials, you can review slides from the lecture that accompanied the initial presentation of these tutorials in the presentations folder.

## Setup Instructions
1) [Install miniconda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) if you don't already have conda
2) [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) if you don't already have git
3) Clone this repository: `git clone https://github.com/nimh-comppsych/qm_tutorials.git`
4) Set-up a conda environment and install packages:  
  ```cd qm_tutorials;
     conda create -p ./env python numpy matplotlib pandas scipy jupyter notebook;
     conda activate ./env
     conda install pytorch torchvision -c pytorch
     pip install pyro-ppl
     mkdir code
     cd code
     git clone https://github.com/compmem/RunDEMC
     pip install -e ./RunDEMC
     cd ..
     ```
5) Start a juypter notebook server: `jupyter notebook`
6) Open up the notebooks in the notebooks directory


##Contributors (in alphabetical order):  
 
Adam Fenton, Computational Memory Lab, University of Virginia. 
Dylan Nielson, Section on Clinical and Computational Psychiatry, National Institutes of Mental Health Intramural Research Program  
Dipta Saha, Section on Clinical and Computational Psychiatry, National Institutes of Mental Health Intramural Research Program  
Per Sederberg, Computational Memory Lab, University of Virginia. 
Charles Zheng, Machine Learning Team, National Institutes of Mental Health Intramural Research Program  