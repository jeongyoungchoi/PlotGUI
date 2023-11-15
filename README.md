# PlotGUI

Author  : JY Choi

Version : 0.9.1

HOW TO USE:

1. Press "Load Data" button and search for a file (.dat/.csv) to upload
2. Select independent (x) and dependent (y) variables (If only one is selected, it is plotted against the number of samples)
	2-1. Adjust multiplier if necessary
	2-2. Remove offset in x and/or y by removing the check in the "Offset" checkbox
3. Filter data (to be added)
4. Select variable to categorise the data, if needed
	4-1a. Overlay plots by pressing the "Enable" checkbox and select the number of plots to display
	4-1b. Select a value for the category variable for each plots
	4-2a. For sensitivity plots enable linear regression by pressing the "Enable" checkbox
	4-2b. Remove the check in the "Enable" checkbox to skip saving the linear regression results
5. Configure plot options
	5-1. Edit axes labels manually by pressing the "Enable" checkbox
	5-2. Enable grid option by pressing the "Enable" checkbox
6. Press "Plot" button to plot, or apply changes to the plot
7. Press "Save" button to save the displayed figure

NOTES:

- .dat files need to have dot (.) as decimal separator instead of comma (,)
- Linear regression ignores the preferences set to offset option
- Latex expressions are recognised for (manual) axes labels if they are within $$
