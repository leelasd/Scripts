Scripts
=======

This repository contains various python programs and packages created to fulfill the needs for various research projects. As such, they come with any sort of warranty. Admittedly they have been sparsely tested.

They were written to be used with python version 2.7 and requires the following packages 
* [numpy](http://www.numpy.org/)
* [scipy](http://www.scipy.org/)
* [matplotlib](http://www.matplotlib.org/)

Most of the programs are dependent on the sgenlib package, and therefor the PYTHONPATH environmental variable needs to be amended to include the installation path of this repository. Assuming this repository was downloaded to a folder called $SCRIPT this can be accomplished with.

```
export PYTHONPATH=$PYTHONPATH:$SCRIPTS 
```

It is recommended to put this is in a source file, e.g. `.bashrc` that is loaded automatically. 
