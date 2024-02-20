# Plant-Disease-Detection-using-Hyperspectral-Imaging-and-AI

### Introduction

This project harnesses the power of hyperspectral imaging and artificial intelligence to assess the quality and detect diseases in plants. Drawing inspiration from the principles outlined in "Application of Hyperspectral Imaging Systems and Artificial Intelligence for Quality Assessment of Fruit Vegetables and Mushrooms" (Review_paper.pdf)​​. The project aims to revolutionize agricultural practices by providing a reliable, non-invasive method for early disease detection.

### Preprocessing Phase
A critical step in our project is the preprocessing of hyperspectral imaging data. This phase involves several key steps:

1. Data Acquisition and Importing Libraries: We begin by importing essential libraries for data manipulation and visualization.

2. Reading and Analyzing Data: We read the Near-Infrared (NIR) and Red band data of the hyperspectral images, checking their shapes and types.

3. Data Visualization: Initial visualization of NIR and Red band images is performed to understand their characteristics.

4. Data Normalization: To equalize the value ranges across bands, we employ min-max normalization, enhancing the data’s usability for pattern recognition and prediction algorithms.

5. Image Cropping and NDVI Calculation: The images are cropped to focus on targeted fields, and the Normalized Difference Vegetation Index (NDVI) is calculated to assess plant health.

6. Thresholding for Soil and Plant Segregation: A threshold is determined to differentiate between soil and plant matter, creating a binary image that highlights vegetation.

7. Histogram Analysis: Histograms are plotted for NIR, Red, and NDVI data to analyze the frequency distribution of values, both before and after normalization.

8. Statistical Analysis: We calculate the mean and standard deviation of the flattened NDVI data for further insights.

### Results and Observations
The preprocessing phase yielded several significant observations:

- The normalization process standardized the data range, facilitating easier pattern recognition.
- NDVI calculations were crucial in assessing plant health, with distinct values indicating different health statuses.
- Thresholding effectively separated plant matter from soil, allowing for focused analysis on vegetation.

### Project Scope and Future Work
The project aligns with recent hyperspectral research in the fields of fruits, vegetables, and mushrooms, emphasizing the importance of spectral data preprocessing in AI applications for agricultural quality assessment​​. Future work will involve implementing machine learning algorithms for disease detection and quality assessment, leveraging the preprocessed data to create robust models.

References
- [Deep Learning Applications for Hyperspectral Imaging:A Systematic Review](https://www.researchgate.net/publication/339580294_Deep_Learning_Applications_for_Hyperspectral_Imaging_A_Systematic_Review)
- [DEEP LEARNING TECHNIQUES FOR HYPERSPECTRAL IMAGE ANALYSIS IN AGRICULTURE: A REVIEW](https://arxiv.org/abs/2304.13880)
- [A Review of Advanced Technologies and Development for Hyperspectral-Based Plant Disease Detection in the Past Three Decades](https://www.mdpi.com/2072-4292/12/19/3188)
