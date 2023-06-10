# MeshSplineCNN
This project implements a deep learning pipeline for graph classification using SplineConv in torch_geometric with MPI Faust dataset. This geometric data with spatial features is an appropriate application of SplineConv for constructing a CNN, meaning each kernel has a fully connected set of trainable weight. The algorithm defining the geometric convolution with B-Spline kernels can be found at [Fey, Lenssen, Weichert, M ̈uller (2017) "SplineCNN: Fast Geometric Deep Learning with Continuous B-Spline Kernels" ]([https://link-url-here.org](https://openaccess.thecvf.com/content_cvpr_2018/papers/Fey_SplineCNN_Fast_Geometric_CVPR_2018_paper.pdf)).

![movie](https://github.com/sofiathelima/MeshSplineCNN/assets/91429357/2d433757-d598-417f-ae9e-20810d61ec46)

## Sources Cited
Fey, Matthias, et al. "Splinecnn: Fast geometric deep learning with continuous b-spline kernels." Proceedings of the IEEE conference on computer vision and pattern recognition. 2018.

Bogo, Federica, et al. "FAUST: Dataset and evaluation for 3D mesh registration." Proceedings of the IEEE conference on computer vision and pattern recognition. 2014.
