This repository contains the code used for the paper entitled ["Eye movement artifact correction in infant EEG"](https://www.sciencedirect.com/science/article/pii/S0165027025000469) from the Journal of Neuroscience Methods.

## Abstract:  

### Background:  

Independent Component Analysis (ICA) is a well-established approach to clean EEG and remove the impact of signals of non-neural origin, such as those from muscular activity and eye movements. However, evidence suggests that ICA removes artifacts less effectively in infants than in adults. This study systematically compares ICA and Artifact Blocking (AB), an alternative approach proposed to improve eye-movement artifact correction in infant EEG.  

### Methods:  

We analyzed EEG collected from 50 infants between 6 and 18 months of age as part of the International Infant EEG Data Integration Platform (EEG-IP), a longitudinal multi-study dataset. EEG was recorded while infants sat on their caregivers’ laps and watched videos. We used ICA and AB to correct for eye-movement artifacts in the EEG and calculated the proportion of effectively corrected segments, signal-to-noise ratio (SNR), power-spectral density (PSD), and multiscale entropy (MSE) in manually selected EEG segments with and without eye-movement artifacts.  

### Results:  

On the one hand, the proportion of effectively corrected segments indicated that ICA corrected eye-movement artifacts (sensitivity) better than AB. SNR and PSD indicated that both AB and ICA correct eye-movement artifacts with equal sensitivity. MSE gave mixed results. On the other hand, AB caused less distortion to the clean segments (specificity) for SNR, PSD, and MSE.  

### Conclusion:  

Our results suggest that ICA is more sensitive (i.e., it better removes artifacts) but less specific (it distorts clean signals) than AB for correcting eye-movement artifacts in infant EEG.
