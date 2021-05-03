# ESA-ESRIN_Mosaicking

This repository contains the code of the mosaicking rountine for the hyperspectral 2018 FLEX campaign data developed during my Young Graduate Trainee program at ESA-ESRIN.

The 2018 FLEX campaign data was provided on a harddrive with a number of mosaics already generated. To increase the number of mosaics for Sentinel-2/3 optical product validation, this mosaicking routine ingests the remaining flight lines for mosaicking. The output is stored in an output folder as gri/grd files and later manually copied back onto the harddrive due to their size of up to around 190 GB. Here, the output folder merely contains a symbolic list of all mosaic files. In total, 15 mosaics have been successfully generated. Two of those were corrections of previously corrupt mosaics and an two additional two mosaicking attempts were unsuccessful; one due to different spatial resolutions of each flight line and one due to an unsolved geometry error.

A Mosaicking Flowchart image file illustrates the functioning of the code.
