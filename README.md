# ML4BC

An attempt towards the goal of improving the accuracy of and the time required for breast cancer diagnosis. More efficient the diagnosis, the earlier can doctors kick the tumour's a**. 
The program analyzes several features and on the basis of said analysis, classifies the tumour as either benign or (malignant) cancerous. 
Indeed a small step but sufficient to demonstrate the power of machine learning (in this case, neural networks) and its applications in healthcare. 

## Data set: Breast Cancer Wisconsin (Diagnostic).
1. Attributes: ID number and Diagnosis (M: Malignant, B: Benign).
2. Number of features used: 10.
- Radius (Mean of multiple radii).
- Texture (std. deviation of grayscale values).
- Perimeter.
- Area.
- Smoothness (Local variation in radii lengths).
- Compactness (perimeter^2 / area - 1.0).
- Concavity (Severity of concave parts of the contour).
- Concave points (number of concave parts of the contour).
- Symmetry.
- Fractal dimension (coastline approximatio - 1).

Mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features.
For example, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius. All feature values are recoded with four significant digits.

Distribution: 357 benign, 212 malignant.
