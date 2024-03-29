# Tomograph

<p align="justify">
Tomograph is a software tool designed to perform the assembly of object projections captured from various angles and produce cross-sectional images in 2D. This program operates on the principles of the Radon Transform, which involves the creation of 1D scans to create a sinogram, followed by 2D image reconstruction through reverse Radon transformation. The sinogram can be filtered to remove any blur using a weaving technique.


## Approach
<p align="justify">
Tomograph takes grayscale images as input and uses a parallel emitter/detector model. The algorithm employed for linear transition after successive pixels of a discrete image is Bresenham.
</p>

## Configuration
<p align="justify">
Tomograph provides the ability to configure several elements, such as the step ∆α of the emitter/detector system, the number of detectors (n) for one emitter/detector system, and the width/span of the emitter/detector system (l).
 </p>

 </p>

![alt text](https://github.com/Zajancz/Tomograf/blob/main/Images/Screenshot_1.png)

 
![alt text](https://github.com/Zajancz/Tomograf/blob/main/Images/Screenshot_2.png)
