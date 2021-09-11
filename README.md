# Gender Prediction from Voice Attributes

This is a Machine Learning Classification Problem <br>

Using the Voice Attributes, we are classifying whether the Gender is Male or Female.

## Attributes

1 target variable: label (male or female)

20 independent variables:
1. meanfreq: mean frequency of the voice audio of the person (in kHz)
2. sd: standard deviation of the frequency of the voice audio
3. median: median frequency of the voice audio (in kHz)
4. Q25: first quantile (in kHz)
5. Q75: third quantile (in kHz)
6. IQR: interquantile range (in kHz)
7. skew: Skewness refers to a distortion or asymmetry that deviates from the symmetrical bell curve, or normal distribution
8. kurt: Kurtosis is a statistical measure that defines how heavily the tails of a distribution differ from the tails of a normal distribution.
9. sp.ent: spectral entropy
10. sfm: spectral flatness
11. mode: mode frequency
12. centroid: frequency centroid (see specprop)
13. meanfun: mean fundamental frequency measured across acoustic signal
14. minfun: minimum fundamental frequency measured across acoustic signal
15. maxfun: maximum fundamental frequency measured across acoustic signal
16. meandom: mean of dominant frequency measured across acoustic signal
17. mindom: minimum of dominant frequency measured across acoustic signal
18. maxdom: maximum of dominant frequency measured across acoustic signal
19. dfrange: range of dominant frequency measured across acoustic signal
20. modindx: modulation index

## Models Accuracy
* Support Vector Machine (74%)
* Random Forest (98%)
