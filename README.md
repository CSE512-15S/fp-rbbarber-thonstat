# Visualizing Hydrophone Data 
### Ramona Barber, Travis Thonstad {rbbarber, thonstat}@uw.edu 
## Overview
Underwater noise generated by river, ocean or tidal turbines has the potential to affect fish and marine life. The noise may lead to injury, avoidance, attraction or behavioral modifications. It is essential to understand the relationship between turbine placement and noise generated to inform design and siting decisions.

The visualization explores the way different frequency bands of the recorded signals attenuate in the spatial domain for different turbine operating conditions, and asks if this is affected by the shape and depth of the riverbed, the frequency of the signal, or other conditions. The visualization is created for experts in the field as a tool to inform design and siting decisions. Several separate, dynamically linked images convey both the frequency characteristics of the hydrophone signal and how the magnitude of the recorded pressures change with distance from the turbine.
* The user can choose the frequency range and the data record by brushing and selecting.
* The cross-flow amplitudes along the hydrophone’s path can be selected by brushing.
* Linking between the panels helps the user stay oriented across the multiple windows.

![alt tag]()

Poster, Final Paper

Acknowledgement: Access to this dataset was provided by Dr. Brian Polagye and Paul Murphy, and their assistance is gratefully acknowledged.

## Running Instructions
Access our visualization at http://cse512-15s.github.io/fp-rbbarber-thonstat/ or download this repository and run python -m SimpleHTTPServer 9000 and access this from http://localhost:9000/.

## Work Breakdown
The work was fragmented into smaller subtasks and they were divided between group members. Interactions within each element of the visualization were coded separately. The final tool was constructed from the separate elements and additional tiem was required to link the plots together. 

1.Off-line data processing and csv creation (thonstad)
2.Visualization coding
   * Spatial Information Window (thonstad)	
   * Frequency Content Window (thonstad)
   * Intensity Content Windows (barber)
   *Linking between windows (barber)
3. Github (barber)





