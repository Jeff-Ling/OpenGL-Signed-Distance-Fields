# OpenGL-Signed-Distance-Fields
CIS 561 - Signed Distance Fields and Subsurface Scattering

## Signed Distance Fields (SDF)
 - Implemented a raymarching function to perform sphere-marching, capturing intersection points and material properties.
 - Developed creative SDF models by assembling intricate scenes using multiple SDF functions and geometric transformations, while also incorporating a custom BSDF function to assign materials.

<div align="center">
<img width="500px" src=https://github.com/CIS-4610-2024/homework-09-signed-distance-fields-Jeff-Ling/assets/74678923/f6701978-47f3-48ec-83b8-18991305d84c>
</div>


## Subsurface Scattering (SS)  
 - Implemented subsurface scattering and integrated it with PBR results. Utilized the SDF-approximated ambient occlusion formula to calculate the ambient occlusion of PBR.

| w/ SS     | w/o SS     |
| ----------| ------     |
| ![image](https://github.com/CIS-4610-2024/homework-09-signed-distance-fields-Jeff-Ling/assets/74678923/329212b9-5ee9-4aed-81e8-d5cd18034bf1) | ![image](https://github.com/CIS-4610-2024/homework-09-signed-distance-fields-Jeff-Ling/assets/74678923/4679242d-5162-4709-bd66-934d66479e0f)|  


## Repeating the Model Through Space  
 - Utilized a grid-based SDF repetition function to duplicate models within the scene.

| <img width="500px" src=https://github.com/CIS-4610-2024/homework-09-signed-distance-fields-Jeff-Ling/assets/74678923/fb1bc47d-5f7e-45a7-bdc3-d0d4f950c940>  | <img width="500px" src=https://github.com/CIS-4610-2024/homework-09-signed-distance-fields-Jeff-Ling/assets/74678923/1d752677-0e36-45e5-890c-568817f95d61> |
|:--:|:--:|
