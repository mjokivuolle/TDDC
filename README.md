# TDDC
Time-dependent diffusion contrast (TDDC) implementation in Matlab with some example data.

The function TDDContrast.m takes two diffusion-weighted MR images as input and calculates the TDDC as defined in the original publication [1]. The input images should have otherwise equal aquisition parameters except the effective diffusion time, which should be different. Minimum two b-values per input image are required: b = 0 s/mm^2 and a non-zero b-value. The TDDC is calculated per b-value. This implementation of TDDC has been initially tested on clinical MRI systems [1] and subsequently validated against histology in glioblastoma (Manuscript in preparation) and oral squamous cell carcinoma (Manuscript in preparation).

# How to cite
Jokivuolle M, Mahmood F, Madsen KH,Harbo FSG, Johnsen L, Lundell H. Assessing tumor microstructure with time-dependent diffusion imaging: Considerations and feasibility on clinical MRI and MRI-Linac. Med Phys. 2024;1-16. https://doi.org/10.1002/mp.17453

# References
[1] Jokivuolle M, Mahmood F, Madsen KH,Harbo FSG, Johnsen L, Lundell H. Assessing tumor microstructure with time-dependent diffusion imaging: Considerations and feasibility on clinical MRI and MRI-Linac. Med Phys. 2024;1-16. https://doi.org/10.1002/mp.17453
