# gromacs-conda

Anaconda recipe for [Gromacs](https://www.gromacs.org).



## Building and uploading to anaconda
```
conda install conda-build
conda install anaconda-client
anaconda login

conda-build freesasa
anaconda upload path_to_package
```


## Installing from Anaconda cloud

```
conda install -c intbio freesasa
```
