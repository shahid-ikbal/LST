# LST
Land Surface Temperature (LST) Analysis for Pakistan (2024)
This Google Earth Engine (GEE) script calculates and visualizes the mean Land Surface Temperature (LST) for Pakistan from January 1, 2024, to November 30, 2024, using the MODIS dataset (MODIS/006/MOD11A2).


Compute the mean LST across the defined time period.
Filter cloud-free pixels for accurate analysis.
Convert temperature data from Kelvin to Celsius.
Mask out invalid temperature values (e.g., extreme outliers).
Visualize the LST distribution across Pakistan on the GEE map.
Add a color-coded legend to enhance map interpretation.
This analysis is helpful for:

Research in climatology and environmental studies.
Monitoring temperature trends across Pakistan.
Supporting academic publications and reports.
Features
Dataset Used:

MODIS (MOD11A2) 8-day LST composite images.
Time Range:

January 1, 2024, to November 30, 2024.
Region of Interest:

Pakistan, based on the FAO GAUL dataset.
Output:

Mean LST values displayed on the GEE map.
A color gradient (blue to red) representing temperatures from 10°C to 50°C.
A clear legend to interpret the temperature ranges.
Key Operations:

Cloud masking for better accuracy.
Conversion of LST data from Kelvin to Celsius.
Clipping the data to Pakistan's boundary.
Visualization
The script centers the map on Pakistan and overlays the mean LST layer.
The legend includes five key temperature points: 10°C, 20°C, 30°C, 40°C, 50°C.
A gradient palette helps visualize temperature variations, from cooler regions (blue) to warmer regions (red).
How to Use
Open the Google Earth Engine Code Editor.
Copy and paste the script into the editor.
Run the script to:
View the mean LST analysis directly on the map.
Observe the color-coded legend for interpretation.
Limitations
The script currently focuses on mean LST values. If required, you can modify it to compute other statistics (e.g., median or max).
Temperature values are capped between 10°C and 50°C for visualization purposes. Adjust as needed for specific use cases.
