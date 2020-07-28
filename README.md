# KernelPCA
Kernel Principal Component Analysis is implemented from scratch in Python.
KPCA is a non-linear dimensionality reduction method using kernels. Here KPCA is implemented using polynomial and rbf kernels.
Instantiate the KPCA class:
```
kpca = KPCA(n_comps = 10, kernel='poly', degree=2) # for using a polynomial kernel of degree 2
```
To create the vector bases for the reduced dimension(dimension = n_comps)
```
kpca.fit(Input_Array)
```
To transform an array to the reduced dimension space
```
kpca.transform(Array) 
```
