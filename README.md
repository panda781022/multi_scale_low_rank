# Multi-scale Low Rank Matrix Decomposition Code
This is a collection of codes in C or in MATLAB to reproduce some of
the results that are described in the paper:
Frank Ong and Michael Lustig
"Beyond Low Rank + Sparse: Multi-scale Low Rank Matrix Decomposition"
https://arxiv.org/abs/1507.08751

You are encouraged to modify or distribute this code in any way you want. 
However, please acknowledge this code and cite the papers appropriately. 
For any questions about the code, please contact me (Frank Ong) at:
frankong@berkeley.edu. 


##MATLAB Demos:

      demo_hanning_decom: Perform Multi-scale Low Rank Decomposition on a synthetic matrix with hanning matrices

      demo_face_decom: Perform Multi-scale low rank decomposition on a face image dataset

      demo_dce_mri_decom: Perform Multi-scale low rank decomposition on a fully sampled Dynamic Contrast Enhanced image dataset


##C Demos

Demos of the multi-scale low rank applied on surveillance videos and
rating matrices are absent in this Matlab package as they are simply too
slow to run on MATLAB. They are/will be available along with the
Berkeley Advanced Reconstruction Toolbox (written in C):
     https://github.com/mikgroup/bart




