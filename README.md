# A-Bezier-curve-based-retracking-algorithm-for-retrieving-sea-ice-freeboard

A new method called Bézier curve fitting (BCF) for approximating CryoSat-2 (CS-2) SAR-mode waveform is developed to optimize the retrieval of surface elevation of both sea ice and leads for the period of late winter/early spring. We found that best results are achieved when the retracking points are fixed on positions at which the rise of the fitted Bézier curve reaches 70% of its peak in case of leads, and 50% in case of sea ice.

In this place, we updownload the codes about 'A-Bezier-curve-based-retracking-algorithm-for-retrieving-sea-ice-freeboard'. This code is based on MATLAB platform, the details can be found in Article 'A new retracking algorithm for retrieving sea ice freeboard from CryoSat-2 radar altimeter data during winter-spring transition', which has been published in Remote Sensing, doi:10.3390/rs11101194.

About the using of this code:

Input: CryoSat-2 SAR-mode Level-b data; CryoSat-2 SAR-mode Level-2I data; One output_file path.
Output: Data in ESRI format, ArcGIS is suggested to process these data.
Valiation data: Operational IceBridge mission, source: https://nsidc.org/icebridge/portal/.
Other detaied processing steps can be seen in Paper mentined above

Example data are also provided here.

For now, the core codes are being maintained and upgraded, and will be published soon.
