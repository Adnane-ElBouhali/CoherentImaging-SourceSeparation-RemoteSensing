# Coherent Imaging, Source Separation and Remote Sensing Practicals

This repository contains practical works completed during the second year of studies at Télécom Paris for the course **IMA207 - Imagerie cohérente, séparation de source, télédétection et applications industrielles** (Coherent Imaging, Source Separation, Remote Sensing, and Industrial Applications).

## Course Description

This course is structured in two parts:

1. New concepts in image processing (such as coherent imaging, multiplicative noise, source separation) using remote sensing applications as a common thread (SAR imaging, multi-spectral optical imaging, hyperspectral imaging).

2. Industrial applications of image processing and analysis, presented by guest speakers from various companies on topics such as biometrics, photography, non-destructive testing, autonomous vehicles, and more.

The course aims to familiarize students with new concepts in image processing and bridge the gap between theoretical knowledge and practical engineering skills in the field.

## Practical Works

This repository includes the following practical works:

1. **SAR Imaging Introduction**: Familiarization with SAR data and interferometric processing.
   - Visualization of complex data (amplitude and phase)
   - Processing of phase and interferometric data

2. **SAR Statistics**: 
   - Empirical checking of speckle distributions
   - Computation of equivalent number of looks
   - Spatial multi-looking and Lee filter implementation

3. **Hyperspectral Imaging and Blind Source Separation (Part 1)**:
   - Sparsity and geometric understanding of mixing effects
   - Non-blind and blind source separation
   - ISTA algorithm and PALM for Blind Source Separation

4. **Hyperspectral Imaging and Blind Source Separation (Part 2)**:
   - Data generation and manipulation with simple and real hyperspectral datasets
   - Implementation of SPA (Successive Projection Algorithm) for near-separable NMF
   - PLAIN NMF and Minimum Volume NMF

5. **Pansharpening**:
   - Introduction to the pansharpening problem
   - Basic solutions for merging high spatial resolution / low spectral resolution images with low spatial resolution / high spectral resolution images

## Tools and Technologies

The practical works are implemented using Jupyter notebooks, allowing for interactive exploration and analysis of the concepts covered in the course. The following Python libraries are extensively used throughout the practicals:

- NumPy
- Matplotlib
- SciPy
- scikit-image
- scikit-learn
- munkres
- mvalab

Familiarity with these libraries is beneficial for understanding and completing the practical works in this course.

## Note

This repository is for educational purposes and contains practical work completed as part of the IMA207 course at Télécom Paris. The content is based on the 2023-2024 academic year curriculum and may be subject to changes in future iterations of the course.