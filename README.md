# Caustic-Design

Caustic design is a method for finding a surface of glass, or any other transparent object, to produce a desired target caustic image due to light refraction. This project tries to solve that problem by parametrizing glass surface using 2D Fourier Features and running Gradient Descent Optimization. 


Parameters:
1. **Samples**
  This is the number of samples (should be a multiple of the number of pixels within a photo) The recommended number of samples per pixel should be greater than 2^4
2. **Refractive index**
   This is the refractive index of the object that is used to calcualte the caustics
3. **Distance**
  This parameter is the distance between the glass and the projected screen. (Glass side has a length of 2π units, but can be rescaled accordingly)
