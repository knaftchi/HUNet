# HUNet

In order to accurately simulate propagation of ultrasound transcranially, we need an accurate acoustic model of the skull. For the first time we built a deep neural network that elucidates the effect of internal pore structure of human skull in determining its acoustic properties (more specifically speed of sound through the skull in this case). We found that internal pore structure in depth (along the propagation path of focused ultrasound) plays a vital role in its acoustic properties compared to its in-plane pore structures (perpendicular to  the propagation path of focused ultrasound rays). The neural network we have built, HUNet, contains 3D convolutional filters as well as 4D dense blocks inspired by DenseNet. 

```dataPreprocess``` contains the steps taken in preprocessing and cleaning up the data. 

```3DDense``` contains the linear model as well as the neural network details used in this research project. 

```Dense3dconv_analysis``` contains some of the analyses done on the output of the neural network model. 
