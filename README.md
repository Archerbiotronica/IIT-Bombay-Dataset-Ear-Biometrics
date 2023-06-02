# IIT-Bombay-Dataset-Ear-Biometrics
Codes for the IEEE conference paper: 
## A Novel Embedding Architecture and Score Level Fusion Scheme for Occluded Image Acquisition in Ear Biometrics System

# Codes

The three .ipynb files are for the three different models used in the paper. The only difference among the three notebooks is in the deep learning network definition portion. Corresponding html versions of the notebooks are also provided. These notebooks also have the metric curves, whereas the paper only consists of the final scalar metric values. 

# Dataset 

The drive link for obtaining the dataset is provided. The data is stored in a .mat file. All the ear RGB images in the IITB ear dataset are stacked one by one in the .mat file. In the codes this .mat file is loaded and further triplet making for training and computation of metrics at testing stage is done using this file only. Separate images will not be required to run the .ipynb files

# Authors

* Archishman Biswas
* Goutham A.P.
* Saket Pateriya
* Divyang S. Jadav
* Satish Mulleti
* Vikram M. Gadre

# Please cite the following reference paper:

A. Biswas, A. P. Goutham, S. Pateriya, D. S. Jadav, S. Mulleti and V. M. Gadre, "A Novel Embedding Architecture and Score Level Fusion Scheme for Occluded Image Acquisition in Ear Biometrics System," 2023 National Conference on Communications (NCC), Guwahati, India, 2023, pp. 1-6, doi: 10.1109/NCC56989.2023.10068032.


Abstract: Significant progress in the field of ear-based biometrics has been made in recent studies. But methods to deal with degradation caused by hair occlusions during ear image acquisition have not been addressed yet. Use of occluded ear images from both sides can give better or comparable results to that of clean image acquisition from a single side. To test this, in this work we introduce a novel embedding generation network using conventional CNNs along with parallel paths of Learnable Scattering Wavelet Networks. We have shown results of experiments for augmented training of proposed embedding network and score level fusion of both side-ear images to mitigate the effects of hair occlusions in verification and identification tasks. We also show extensive simulation results over closed and open testing sets to analyse the one-shot learning capabilities of our proposed embedding network. The reported performance metrics show the improvement achieved by using our proposed embedding network and fusing both sides of occluded ear images.


URL: https://ieeexplore.ieee.org/document/10068032

