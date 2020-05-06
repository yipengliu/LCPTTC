# Yipeng Liu, Zhen Long, Huyan Huang, Ce Zhu, "Low CP Rank and Tucker Rank Tensor Completion for Estimating Missing Components in Image Data," IEEE Transactions on Circuits and Systems for Video Technology, vol. 30, no. 4, pp. 944-954, 2020. 


Tensor completion recovers missing components of multi-way data. The existing methods use either the Tucker rank or the CANDECOMP/PARAFAC (CP) rank in low-rank tensor optimization for data completion. In fact, these two kinds of tensor ranks represent different high-dimensional data structures. In this paper, we propose to exploit the two kinds of data structures simultaneously for image recovery through jointly minimizing the CP rank and Tucker rank in the low-rank tensor approximation. We use the alternating direction method of multipliers (ADMM) to reformulate the optimization model with two tensor ranks into its two sub-problems, and each has only one tensor rank optimization. For the two main sub-problems in the ADMM, we apply rank-one tensor updating and weighted sum of matrix nuclear norms minimization methods to solve them, respectively. The numerical experiments on some image and video completion applications demonstrate that the proposed method is superior to the state-of-the-art methods.


# demo

demo_test.m for color image completion


# setting up

For setting up, you can add path by the following sentence.

addpath('mylib'); 

