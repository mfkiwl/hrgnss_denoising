# GNSS Denoising

## Description

This repository contains data, training scripts, model architectures and other utilities for creating a U-shaped Convolutional Neural Network trained to denoise high-rate global navigation satellite system data (HR-GNSS).  Descriptions of all files and scripts can be found below.  Further details are available in:

Thomas, A. M., D. Melgar, S. Dybing, and J. Searcy (202?) Deep learning for denoising High-Rate Global Navigation Satellite System data. Submitted to Seismica.

BibTeX:

    @article{thomas202Xhrgnss,
        title={Deep learning for denoising High-Rate Global Navigation Satellite System data},
        author={Thomas, Amanda M and Melgar, Diego, and Dybing, Sydney and Searcy, Jacob},
        journal={Seismica},
    }

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4777132.svg)](https://doi.org/10.5281/zenodo.4777132)

## Requirements

In order to run the scripts you will need [Obspy](https://docs.obspy.org/) (I have version 1.3.0), [Tensorflow](https://www.tensorflow.org/) (I have version 2.8.1), Keras (2.8.0), and other standard python utilities such as numpy, scipy, and matplotlib.  I recommend creating a [conda](https://docs.conda.io/en/latest/) environment and installing packages into it.    

## File Descriptions
* gnss_denoiser_3comp_v1.py - training script for model 1 (described in above reference) 
* gnss_denoiser_3comp_v2.py - training script for model 2 (described in above reference) 
* gnss_denoiser_3comp_v3.py - training script for model 3 (described in above reference) 

