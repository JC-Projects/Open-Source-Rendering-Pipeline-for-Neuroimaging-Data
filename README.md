## An Open Source Rendering Pipeline for Neuroimaging Data
![](https://github.com/JC-Projects/Open-Source-Rendering-Pipeline-for-Neuroimaging-Data/blob/main/Render%20Images%20and%20Animations/Render%20-%20Animation.gif)
![](https://github.com/JC-Projects/Open-Source-Rendering-Pipeline-for-Neuroimaging-Data/blob/main/Render%20Images%20and%20Animations/Render%20-%20Image.png)

**🚧WIP**
-
This pipeline is currently very simple, and whilst it does produce usable renders, I believe significant improvements can be made. Current future plans are as follows:
- Manual masking in InVesalius to improve ventricular detail and allow optional removal of lobes for interior visibility
- Texture painting of regions (particularly lobes) for better use in scientific communication
- Find open access MRI data with more z-levels and detail to reduce horizontal banding
- Potential integration of SPM as a replacement for InVesalius to improve .STL topology and allow more fine manipulation outside of Blender
- Incorporate pipeline for CT and PET data if possible

**🔨TOOLS USED**
- 

 nii2dcm: Used to convert NIFT to DICOM files for InVesalius import

 InVesalius v 3.1.1: Used to QC and mask the converted DICOM file
 
 Blender v4.4: Used to create and modify final render

_<br>_

All work is my own, and any suggestions for improvement or iteration are welcome.
