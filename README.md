# Timex Interval Sensitivity Study
Remote video imagery using shoreline edge detection is widely used in coastal monitoring in order to acquire measurements of nearshore and swash features. Some of these systems are constrained by their long setup time, positioning requirements and considerable hardware costs. As such, there is a need for an autonomous low-cost system (~EUR 500), such as Timex cameras, that can be rapidly deployed in the field, while still producing the outcomes required for coastal monitoring. This research presents an assessment of the effect of the sampling strategy (time-lapse intervals) on the precision of shoreline detection for two low-cost cameras located in a remote coastal area in western Ireland, overlooking a dissipative beach–dune system. The analysis shows that RMSD in the detected shoreline is similar to other studies for sampling intervals ranging between 1 s and 30 s (i.e., RMSDmean for Camera 1 = 1.4 m and Camera 2 = 0.9 m), and an increase in the sampling interval from 1 s to 30 s had no significant adverse effect on the precision of shoreline detection. The research shows that depending on the intended use of the detected shorelines, the current standard of 1 s image sampling interval when using Timex cameras can be increased up to 30 s without any significant loss of accuracy. This positively impacts battery life and memory storage, making the systems more autonomous; for example, the battery life increased from ~10 days to ~100 days when the sampling interval was increased from 1 to 5 s.

## Usage
### Overview
This study builds upon the foundation laid by [CIRN](https://github.com/Coastal-Imaging-Research-Network).
The creation of timestack images, georectification, and shoreline detection can be achieved with the [Quantitative Coastal Imaging Toolbox](https://github.com/Coastal-Imaging-Research-Network/CIRN-Quantitative-Coastal-Imaging-Toolbox). 

### Timelapse Images
The images captured by the timelapse camera can be found [here](Timelapse_Images).

## Citation
Nuyts, S., Farrell, E. J., Fennell, S., & Nash, S. (2024). An Assessment of the Role of the Timex Sampling Strategy on the Precision of Shoreline Detection Analysis. Coasts, 4(2), 347-365. 


