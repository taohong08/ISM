# Iterative Spectral Method ( ISM ) 

Iterative Spectral Method (ISM) was originally proposed in the paper *Iterative Spectral Method for Alternative Clustering*, Wu et al., AISTATS 2018. It is an optimization technique that could be used to solve many HSIC related problems with a Gaussian Kernel. This repository contains an implemented ISM for Kernel Dimensionality Alternative Clustering (KDAC). KDAC was originally proposed in the paper *Iterative Discovery from Multiple Clustering Views*, Niu et al., Transactions on Pattern Analysis and Machine Intelligence, 2014.




## Getting Started

The code is written with python2.7 on a Mint Linux Machine version 17.1. 
The following libraries must be included.

  1. numpy
  2. matplotlib
  3. sklearn
  4. scipy
  
Note: The GPU version is current NOT supported in this release. 

The experiments should run by uncommenting the appropriate experiment within main.py and running the file. 




## Contributors

* **Chieh Wu** , **Stratis Ioannidis**



## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

We would like to acknowledge support for this project from the NSF grant IIS-1546428.

## Citation
```
@inproceedings{wu2017ISM,
  title={Iterative Spectral Method for Alternative Clustering},
  author={Wu, Chieh and Ioannidis, Stratis},
  booktitle={Artificial Intelligence and Statistics},
  year={2017}
}
```
