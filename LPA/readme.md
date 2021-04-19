## Label propagation 
This branch provides an implementation for **Label Propagation** as described in the paper:
>Learning from Labeled and Unlabeled Data with Label Propagation.
>Xiaojin Zhu, Zoubin Ghahramani.
>CMU-CALD-02-107, June 2002.  
>[[Paper]](http://mlg.eng.cam.ac.uk/zoubin/papers/CMU-CALD-02-107.pdf)
>Abstract:
>We investigate the use of unlabeled data to help labeled data in classification. We propose a simple iterative algorithm, label propagation, to propagate labels through the dataset along high density areas defined by unlabeled data. We give the analysis of the algorithm, show its solution, and its connection to several other algorithms. We also show how to learn parameters by minimum spanning tree heuristic and entropy minimization, and the algorithm's ability to do feature selection. Experiment results are promising.
## Requirements
The codebase is implemented in Python 3.7.10. Package versions used for development are just below.
```
pandas  1.1.5
numpy   1.19.5
math    3.7.10  
matlibplot  3.2.2
networkx    2.5.1   
```
## Dataset